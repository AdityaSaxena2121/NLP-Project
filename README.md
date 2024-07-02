# Sentiment Analysis of Movie Reviews – Natural Language Processing

This project focuses on analyzing the sentiment of movie reviews using various Natural Language Processing (NLP) techniques and machine learning models.


## Introduction

The goal of this project is to classify the sentiment of movie reviews as positive or negative. We use Natural Language Processing (NLP) techniques to preprocess the text data and machine learning models to predict the sentiment.

## Dataset

- **Source**: [IMDb Dataset]
- **Description**: The dataset contains movie reviews from IMDb, labeled by sentiment (positive/negative).

## Installation

   **Install dependencies**:
    ```bash
    pip install pandas scikit-learn nltk
    pip install matplotlib seaborn numpy pandas
    ```
    ```

## Usage

1. **Download the dataset** from [IMDb Dataset] and extract it into the project directory.

2. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

3. Open `sentiment_analysis.ipynb` in the Jupyter Notebook interface.

4. **Execute the cells** to perform the analysis and train the models.

## Features

- Data Cleaning and Preprocessing
- Text Tokenization and Vectorization
- Sentiment Classification using Machine Learning Models
- Evaluation of Model Performance

## Results

Key findings and performance metrics of the models will be summarized here. This includes accuracy, precision, recall, F1-score, and any visualizations created during the analysis.

# Precision: 0.90 (90% of the instances predicted as negative were actually negative)
# Recall: 0.87 (87% of the actual negative instances were correctly predicted as negative)
# F1-score: 0.88 (the harmonic mean of precision and recall for the negative class)
# For positive class:

# Precision: 0.87 (87% of the instances predicted as positive were actually positive)
# Recall: 0.90 (90% of the actual positive instances were correctly predicted as positive)
# F1-score: 0.89 (the harmonic mean of precision and recall for the positive class)
# Overall:

# Accuracy: 0.88 (88% of the predictions made by the model were correct across both classes)
# Macro avg: Average precision, recall, and F1-score across all classes. In this case, it's the unweighted mean of precision, recall, and F1-score.
# Weighted avg: Average precision, recall, and F1-score weighted by the support of each class. This is particularly useful in cases of class imbalance.
     

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.
