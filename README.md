# Loan Prediction Model

This project uses a Logistic Regression model to predict loan approval based on various applicant features.

## Dataset

The dataset used is `loan_dataset.csv`. It contains information about loan applicants, including their gender, marital status, income, loan amount, and loan status.

## Preprocessing

- Missing values in numerical columns are filled with the mean.
- Categorical features are encoded using Label Encoding.

## Model Training

- The data is split into training and testing sets (80/20).
- A Logistic Regression model is trained on the training data.

## Evaluation

- Model accuracy is evaluated on both the training and testing sets.

## Usage

1. Upload `loan_dataset.csv` to your Google Colab environment.
2. Run the code cells sequentially.
3. Observe the model accuracy printed at the end.

## Dependencies

- pandas
- numpy
- nltk
- re
- scikit-learn

## Note

- You may need to install NLTK resources: `nltk.download('punkt')`
