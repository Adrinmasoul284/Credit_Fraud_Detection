#Credit Card Fraud Detection

This project implements a simple **Logistic Regression** model to detect fraudulent credit card transactions using the [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

The dataset is highly imbalanced (only 0.17% fraud cases), so we perform **undersampling** of legitimate transactions to create a balanced dataset for training.

##Features
- Uses **Google Colab file upload** to load dataset.
- Data preprocessing & balancing.
- Logistic Regression model for binary classification.
- Accuracy evaluation on training and test data.

##Dataset
The dataset contains:
- **Time**: Seconds elapsed between each transaction and the first transaction in the dataset.
- **V1–V28**: PCA-transformed features (to protect privacy).
- **Amount**: Transaction amount.
- **Class**: Target variable (0 = Legal, 1 = Fraud).

> **Note:** Due to licensing, the dataset is not included in this repository.  
You can download it from Kaggle: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

##How to Run
1. Open this project in **Google Colab** or your local Python environment.
2. Upload the `creditcard.csv` file when prompted.
3. Run all cells to train the model and view accuracy results.

