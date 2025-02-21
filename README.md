# Customer Service Ticket Categorization

## Project Overview
This project builds a machine learning model to categorize customer service tickets based on their `subject` and `body` fields. 
The model will predict:
- **Queue** (The type/category of the request)
- **Priority** (The urgency level of the request)

## Dataset Details
- **Dataset:** `dataset-tickets-multi-lang-4-20k.csv`
- **Key Features Used:** `subject`, `body`
- **Labels to Predict:** `queue`, `priority`
- **Tech Stack:** Python, Scikit-Learn, Pandas, NLTK

- # Notebooks Overview
- **`01_data_preprocessing.ipynb`** → Data cleaning & preprocessing.
- **`02_feature_engineering.ipynb`** → Feature extraction (TF-IDF, embeddings).
- **`03_model_training.ipynb`** → Model training & hyperparameter tuning.
- **`04_model_evaluation.ipynb`** → Model performance analysis.

## 🔧 How to Use
Clone this repository and run:
```sh
pip install -r requirements.txt
jupyter lab
