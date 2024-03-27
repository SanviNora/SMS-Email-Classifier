# SMS-Email Classifier

## Overview
This project aims to classify text messages as either SMS or email. It utilizes machine learning techniques for text classification, specifically focusing on Naive Bayes classifiers. The classifier is trained on preprocessed text data, including text normalization, tokenization, and feature extraction.

## Installation

Before running the app, you need to install the required packages. You can do this by running the following command:

```bash
pip install -r requirements.txt
```
This command reads the `requirements.txt` file and installs all the packages listed in it.

## Running the App
After installing the required packages, you can run the Flask app with the following command:

```bash
python app.py
```

## Data Cleaning

The data cleaning process involves removing missing values, duplicates, and performing alterations to the text data.

## Preprocessing
The preprocessing steps include:

   - Transforming text into lowercase characters.
   - Tokenization of the text using the *NLTK* library.
   - Removing special characters, stopwords, and punctuations.
   - Performing stemming on the text.
```bash
nltk.download('stopwords')
from nltk.corpus import stopwords
```
```bash
import string
string.punctuation
```
```bash
from nltk.stem.porter import PorterStemmer
ps = PorterStemmer()
```

## Model Building
Now that you have obtained the clean analyzed data, the model is ready for traning and testing.

  - Text vectorization using Bag of Words.
  - Configuring `feature extraction`.
  - Training and testing different Naive Bayes classifiers.
  - Evaluating different classifiers to determine the best precision score.

## Streamlit App (for the Website)
To deploy the app on a website using Streamlit:

  - Go to the [Streamlit Documentation]((https://docs.streamlit.io/), and get the `API reference` section to get the template of your choice.
  - Open any open source python IDE.
  - Run the `app.py` file.

## Contributions
Contributions to this project are welcome. Feel free to fork the repository, make improvements, and submit pull requests.

## License
This project is licensed under the MIT License.

## Acknowledgments
Special thanks to the contributors of the NLTK and Scikit-learn libraries.
Inspired by similar projects in the field of natural language processing.
