# Resume Classification using Logistic Regression

## Overview
This project aims to classify resumes into different categories using Natural Language Processing (NLP) techniques and machine learning. It utilizes the TF-IDF vectorization method to transform text data and employs Logistic Regression for classification.

## Dataset
The dataset used for this project is `https://www.kaggle.com/datasets/gauravduttakiit/resume-dataset`, which contains two main columns:
- `Resume`: Text data containing the content of resumes.
- `Category`: The classification label for each resume.

## Dependencies
Ensure you have the following libraries installed:

```bash
pip install pandas scikit-learn nltk
```

## Preprocessing Steps
1. **Text Cleaning**: Removes special characters and numbers.
2. **Lowercasing**: Converts text to lowercase.
3. **Tokenization**: Splits text into words.
4. **Stopword Removal**: Eliminates common words that do not contribute to classification.

## Model Training
- **TF-IDF Vectorization** is used to convert text into numerical features.
- **Train-Test Split**: The dataset is split into 80% training and 20% testing data.
- **Logistic Regression** is used for classification.
- **Accuracy Score** is used to evaluate model performance.

## How to Run
1. Load the dataset from `https://www.kaggle.com/datasets/gauravduttakiit/resume-dataset`
2. Preprocess the text data.
3. Train the Logistic Regression model.
4. Evaluate the model using accuracy metrics.

## Expected Output
The program prints the accuracy of the model on the test dataset.

```bash
Accuracy: 0.99
```

## Future Improvements
- Implement advanced models like Random Forest or Deep Learning.
- Use word embeddings for better text representation.
- Hyperparameter tuning for better accuracy.





