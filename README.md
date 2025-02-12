# Transaction and Fraud Data

This directory contains transaction and fraud data for analysis.

## Files

* **transactions_month_6.csv:** Transaction data for June.
* **transactions_month_7.csv:** Transaction data for July.
* **transactions_month_8.csv:** Transaction data for August.
* **...** (And so on for other months)
* **fraud.csv:** Fraudulent transaction data.

## Data Description

**Transaction Files:**

Each transaction file contains information about transactions made during a specific month. The columns include:

* **Trans_date_trans_time:** Timestamp of the transaction (date and time).
* **Cc_num:** Unique customer identification number.
* **Merchant:** The merchant involved in the transaction.
* **Category:** Transaction type (e.g., personal, childcare).
* **Amt:** Transaction amount.
* **First:** Cardholder's first name.
* **Last:** Cardholder's last name.
* **Gender:** Cardholder's gender.
* **Street:** Cardholder's street address.
* **City:** Cardholder's city of residence.
* **State:** Cardholder's state of residence.
* **Zip:** Cardholder's zip code.
* **Lat:** Latitude of cardholder's location.
* **Long:** Longitude of cardholder's location.
* **City_pop:** Population of the cardholder's city.
* **Job:** Cardholder's job title.
* **Dob:** Cardholder's date of birth.
* **Trans_num:** Unique transaction identifier.
* **Unix_time:** Transaction timestamp (Unix format).
* **Merch_lat:** Merchant's location (latitude).
* **Merch_long:** Merchant's location (longitude).

**Fraud File:**

* **Is_fraud:** Fraudulent transaction indicator (1 = fraud, 0 = legitimate).
The fraud file contains information about fraudulent transactions. The columns are the same as in the transaction files, but it only includes transactions that have been identified as fraudulent.

## Usage

These data files can be used for various data analysis and machine learning tasks, such as:

* **Fraud detection:** Building models to identify fraudulent transactions.
* **Customer segmentation:** Grouping customers based on their transaction behavior.
* **Spending analysis:** Understanding spending patterns across different categories and demographics.
* **Risk assessment:** Evaluating the risk associated with different transactions.

## Disclaimer

This data is for demonstration purposes only and may not reflect real-world scenarios.
