# Titanic Survival Prediction

This project aims to predict the likelihood of survival for passengers on the Titanic using various supervised learning models. The dataset includes features such as name, age, gender, socio-economic class, and other relevant factors. The objective is to identify which sorts of people were more likely to survive.

## Project Structure

- `train.csv`: Training dataset containing features and target labels (Survived).
- `test.csv`: Test dataset for making predictions.
- `test_predictions.csv`: Predicted labels for the test dataset.
- `Supervised_Modeling.ipynb`: Jupyter notebook containing the data preprocessing, model training, evaluation, and prediction code.

## Models Used

The following supervised learning models were used and evaluated in this project:
- Logistic Regression
- Random Forest
- Gradient Boosting
- K-Nearest Neighbors
- Support Vector Machine

## Evaluation Metrics

The models were evaluated using cross-validation with the following metrics:
- Accuracy
- Precision
- Recall
- F1-score

## Results

The model with the best performance (Gradient Boosting) was selected as the best model.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/f2-bigdeli/Titanic-Survival-Prediction-Supervised-Learning.git
   cd titanic-survival-prediction
