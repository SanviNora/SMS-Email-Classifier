# SMS-Email Classifier
## Installation

Before running the app, you need to install the required packages. You can do this by running the following command:

```bash
pip install -r requirements.txt
```
This command reads the requirements.txt file and installs all the packages listed in it.

## Running the App
After installing the required packages, you can run the Flask app with the following command:

```bash
python app.py
```
## Preprocessing

1. Go to the [Hugging Face website](https://huggingface.co/).
2. Sign in or create a new account.

## Tokenization

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Sign in or create a new Google Cloud account.
3. Create a new project or select an existing one.

## Model Building
Now that you have obtained both keys, configure the application with these keys.

1. Open the `app.py` file in the project.
2. Replace the `HUGGING_FACE_ACCESS_KEY` variable with your Hugging Face read-only access key.
3. Replace the `GOOGLE_API_KEY` variable with your Google Cloud Console API key.

```python
# app.py


# Streamlit App
GOOGLE_API_KEY = 'your_google_api_key'
