# YELP RESTAURANT REVIEWS - TEXT MINING PROJECT

## 📄 Project Overview
This project applies text mining and machine learning to Yelp restaurant reviews to determine whether a review indicates a positive recommendation. By analyzing customer feedback and ratings, we aim to classify reviews as either "Recommended" or "Not Recommended." This model can help businesses analyze customer sentiment and improve decision-making based on customer feedback.

## 🗂️ Dataset
- **Source:** [Kaggle - Yelp Restaurant Reviews](https://www.kaggle.com/datasets/farukalam/yelp-restaurant-reviews)
- **Content:** The dataset includes Yelp reviews of restaurants with ratings on a 1-5 scale. Reviews rated 4 or 5 indicate a recommendation.
  
## 🛠️ Project Workflow
The project involves the following steps:

1. **Data Preprocessing** (`Yelp_Restaurant.py`)
   - Text cleaning: Removing punctuation, stop words, and applying tokenization.
   - Data transformation: Converting the cleaned text into a structured numerical format suitable for machine learning algorithms.

2. **Model Training**
   - Implements two machine learning classification models for text data.
   - Hyperparameter tuning and training for optimal performance on the labeled dataset.

3. **Evaluation**
   - Model performance is evaluated using metrics like accuracy, precision, recall, and F1 score.
   - Based on evaluation results, the project selects the best model for classifying customer reviews as recommendations or not.

## 📊 Technologies Used
- **Programming Language:** Python
- **Libraries:** 
  - **Pandas** for data manipulation.
  - **NumPy** for numerical operations.
  - **Scikit-learn** for model building and evaluation.
  - **NLTK** for natural language processing tasks like tokenization and stop-word removal.

