# Online Payment Fraud Detection



## Overview

Online payments have become the predominant mode of transactions worldwide. However, this convenience has also brought about an increase in payment fraud. The objective of this project is to detect and classify fraudulent and non-fraudulent transactions using historical data sourced from Kaggle.

## Dataset
LInk for dataset used : https://drive.google.com/drive/folders/1gW-UlbdzgNaTo10klanWhc0ln3xR9bF2?usp=sharing

The dataset used in this project contains 10 variables:

- **step**: Represents a unit of time where 1 step equals 1 hour.
- **type**: Type of online transaction (e.g., payment, transfer, etc.).
- **amount**: The amount of the transaction.
- **nameOrig**: Customer initiating the transaction.
- **oldbalanceOrg**: Customer's balance before the transaction.
- **newbalanceOrig**: Customer's balance after the transaction.
- **nameDest**: Recipient of the transaction.
- **oldbalanceDest**: Recipient's initial balance before the transaction.
- **newbalanceDest**: Recipient's balance after the transaction.
- **isFraud**: Binary indicator (1 for fraud, 0 for non-fraudulent transaction).

## Methodology

Machine learning techniques were employed to analyze the dataset and develop models capable of identifying fraudulent activities. Key steps included data preprocessing, exploratory data analysis, feature engineering, model training using algorithms like Random Forest, and evaluation of model performance.

## Project Structure

The project structure includes the following files and directories:

- **data/**: Directory containing the dataset files.
- **notebooks/**: Jupyter notebooks used for data analysis and model development.
- **scripts/**: Python scripts for preprocessing, training, and evaluating models.
- **README.md**: This file providing an overview of the project.

## Requirements

Ensure you have the following libraries installed to run the project:

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

You can install these dependencies using pip:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
