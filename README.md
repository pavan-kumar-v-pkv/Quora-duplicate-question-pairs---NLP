
# Quora Duplicate Question Pairs - NLP

This repository contains solutions for the Quora Question Pairs problem, which aims to identify whether two questions asked on Quora are duplicates (i.e., have the same meaning).

## Notebooks

### 1. Quora_Question_Pairs_RandomForest.ipynb
This notebook implements a Random Forest approach for duplicate question detection. It includes:
- Exploratory Data Analysis (EDA)
- Feature engineering (length, word counts, common words, etc.)
- Bag-of-Words using CountVectorizer
- Random Forest classification
- Analysis of feature importance and model accuracy

### 2. NLP-based Approach (Coming Soon)
A separate notebook will be added to implement advanced NLP techniques (such as TF-IDF, word embeddings, or deep learning models) for duplicate question detection.

## Dataset
The dataset used is from the [Quora Question Pairs Kaggle competition](https://www.kaggle.com/competitions/quora-question-pairs/overview).
- `train.csv`: Contains pairs of questions and a binary label indicating if they are duplicates.

## How to Use
1. Open the `Quora_Question_Pairs_RandomForest.ipynb` notebook to explore the Random Forest solution.
2. The NLP notebook will be available soon for more advanced methods.

## Requirements
- Python
- pandas, numpy, scikit-learn, seaborn, matplotlib

## License
MIT
