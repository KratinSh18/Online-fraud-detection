# Online Payment Fraud Detection

## Introduction
Online payment is the most popular transaction method in the world today. However, with an increase in online payments also comes a rise in payment fraud. The objective of this project is to train machine learning models for identifying fraudulent and non-fraudulent payments using historical transaction data from Kaggle.

The dataset consists of 10 variables:

- **step**: Represents a unit of time where 1 step equals 1 hour.
- **type**: Type of online transaction.
- **amount**: The amount of the transaction.
- **nameOrig**: Customer starting the transaction.
- **oldbalanceOrg**: Balance before the transaction.
- **newbalanceOrig**: Balance after the transaction.
- **nameDest**: Recipient of the transaction.
- **oldbalanceDest**: Initial balance of the recipient before the transaction.
- **newbalanceDest**: The new balance of the recipient after the transaction.
- **isFraud**: Indicates if the transaction is fraudulent (1) or not (0).

## Python Libraries
- pandas
- numpy
- seaborn
- matplotlib
- tabulate
- sklearn

Random Forest and Naive Bayes were used to identify online payment fraud due to the large dataset.

![image](https://user-images.githubusercontent.com/118715799/210950017-e4d317e0-6bf4-4ecd-8313-9b8121e04e9f.png)

Read the complete Online Payment Fraud Detection project [here](https://github.com/seuwenfei/Online-payment-fraud-detection/blob/main/online-payment-fraud-detection.ipynb).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/KratinSh18/fraud-detection.git
   cd fraud-detection
