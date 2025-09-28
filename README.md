# NLP Machine Learning Project

This repository contains various Natural Language Processing (NLP) projects and experiments, including text preprocessing, representation, word embeddings, classification, and POS tagging. Datasets are not included due to size constraints.

## Structure
- `01.Text_preprocessing.ipynb`: Text cleaning and preprocessing steps
- `02.Text_Representation.ipynb`: Text representation techniques
- `03.Word2Vec.ipynb`: Word2Vec embeddings
- `04.Text_Classifiaction.ipynb`: Text classification models
- `05.POS.ipynb`: Part-of-speech tagging
- `environment.yml`: Project dependencies
- `Notes.txt`: Project notes
- `GOT Dataset/`, `Quora duplicate Pair Project/`: Example dataset folders (ignored in git)

## How to Run
1. Clone the repository:
   ```
   git clone https://github.com/darshan-pareek/NLP.git
   ```
2. Install dependencies:
   ```
   conda env create -f environment.yml
   conda activate nlp
   ```
3. Open notebooks in Jupyter or VS Code and run cells.

## Datasets
Large datasets (e.g., IMDB, GOT, Quora) are not included in the repository. Please download them separately if needed.

## Quora Duplicate Pair Project
This project aims to identify whether pairs of questions from Quora are duplicates (i.e., have the same meaning) or not. It uses NLP techniques for preprocessing and feature extraction, applies both machine learning and deep learning approaches, and predicts duplicate status using models such as Random Forest. The workflow includes:

Data cleaning and text normalization
Feature engineering with NLP methods
Model training and evaluation (Random Forest, etc.)
Analysis of same and different type question pairs

## License
This project is for educational purposes.
