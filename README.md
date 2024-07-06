# Online Payment Fraud Detection

## Overview

Online payment is the most popular transaction method in the world today. However, with an increase in online payments also comes a rise in payment fraud. The objective of this study is to identify fraudulent and non-fraudulent payments using historical transaction data. This project uses a dataset from Kaggle, which contains historical information about fraudulent transactions.

## Dataset

The dataset consists of 10 variables:

- **step**: represents a unit of time where 1 step equals 1 hour.
- **type**: type of online transaction.
- **amount**: the amount of the transaction.
- **nameOrig**: customer starting the transaction.
- **oldbalanceOrg**: balance before the transaction.
- **newbalanceOrig**: balance after the transaction.
- **nameDest**: recipient of the transaction.
- **oldbalanceDest**: initial balance of the recipient before the transaction.
- **newbalanceDest**: the new balance of the recipient after the transaction.
- **isFraud**: indicates if the transaction is fraudulent (1) or not (0).

## Project Structure


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/KratinSh18/fraud-detection.git
   cd fraud-detection

python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`

pip install -r requirements.txt
