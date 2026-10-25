# Text Preprocessing

An experimental NLP project that walks through basic text preprocessing with NLTK and scikit-learn: sentence and word tokenization, stemming, lemmatization, stopword removal, and bag of words (default and binary).

The work lives in `preprocessing.ipynb`.

## Setup

1. Create a conda environment in the project folder:

   ```bash
   conda create -p ./venv python=3.12
   ```

2. Activate it:

   ```bash
   conda activate ./venv
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## NLTK data

The notebook downloads the NLTK resources it needs (`punkt_tab`, `wordnet`, `stopwords`) when you run it, so there is nothing extra to install.

## Running the notebook

Open `preprocessing.ipynb` in your IDE or Jupyter and run the cells from top to bottom. Make sure the `./venv` environment is selected as the kernel.
