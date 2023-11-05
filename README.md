# Compound SL Trial
## Objective
Develop a tool that analyses a given text and suggests improvements based on the similarity to a list of "standardised" phrases. These standardised phrases represent the ideal way certain concepts should be articulated, and the tool should recommend changes to align the input text closer to these standards.

## Technology used
This project implemented with following: 
  - Project was created in Jupyter Notebook 
  - Gensim library for  utilizatig pretrained GoogleNews-vectors-negative300 model
  - NLTK library for text preprocessing (stopwords, tokenization)
  - sklearn library for for calculation cosine similarity

## Intallation
Please ensure following dependencies installed
### Anaconda Navigator 2.4.0 (Python 3.10.9)

### PIP Dependencies:
!pip install nltk==3.8.1 regex==2023.10.3 scikit-learn==1.3.2 gensim==4.3.2

### GoogleNews-vectors-negative300 model Download:
import gensim.downloader as api
path = api.load("word2vec-google-news-300", return_path=True) 

### NLTK Dependencies:
nltk.download("punkt")
nltk.download('stopwords')

## Usage
In order to run code please install alldpendencied and lunch Jupyter Notebook GUI.


