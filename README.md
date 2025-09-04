
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


### 2. Quora_Question_Pairs_2.ipynb (Advanced NLP Feature Engineering)
This notebook implements advanced NLP feature engineering for duplicate question detection, including:
- Text preprocessing (lowercasing, decontracting, removing HTML, punctuation, etc.)
- Feature engineering: length, word counts, common words, word share
- Advanced features: token-based, length-based, and fuzzy matching features
- Visualization with t-SNE
- Model training with Random Forest and XGBoost
- Confusion matrix analysis and model comparison

## Dataset
The dataset used is from the [Quora Question Pairs Kaggle competition](https://www.kaggle.com/competitions/quora-question-pairs/overview).
- `train.csv`: Contains pairs of questions and a binary label indicating if they are duplicates.

## How to Use
1. Open the `Quora_Question_Pairs_RandomForest.ipynb` notebook to explore the Random Forest solution.
2. Open the `Quora_Question_Pairs_2.ipynb` notebook for advanced NLP feature engineering and model comparison.

## Requirements
- Python
- pandas, numpy, scikit-learn, seaborn, matplotlib, nltk, distance, fuzzywuzzy, xgboost

## License
MIT

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
