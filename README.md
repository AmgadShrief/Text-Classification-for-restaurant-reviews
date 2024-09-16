# Text Classification on Restaurant Reviews

This project demonstrates a basic text classification task using a dataset of restaurant reviews. The aim is to build a model that classifies whether a review is positive or negative.

## Dataset

The dataset used in this project is `restaurant_reviews.tsv`, a collection of restaurant reviews where each review is labeled as either positive or negative. The dataset is organized as follows:
- **Review**: The text of the review.
- **Label**: The sentiment of the review (Positive or Negative).

## Project Structure

The notebook is structured into the following sections:

1. **Data Loading**: 
   - Loading the dataset and performing initial inspections.
   - Handling missing values and cleaning the data.

2. **Data Preprocessing**:
   - Text cleaning: Removing punctuation, stopwords, and performing tokenization.
   - Converting text data into a format suitable for machine learning models using methods such as Bag of Words (BoW) or TF-IDF.

3. **Model Selection**:
   - Exploring different classifiers (e.g., Logistic Regression, Random Forest, Naive Bayes).
   - Training the models on the preprocessed dataset.

4. **Model Evaluation**:
   - Using metrics such as accuracy, precision, recall, and F1-score to evaluate model performance.
   - Visualizing confusion matrices to understand model errors.

6. **Results**:
   - Final model selection based on performance metrics.
   - Discussion on the results and possible improvements.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/text-classification-reviews.git
   cd text-classification-reviews
