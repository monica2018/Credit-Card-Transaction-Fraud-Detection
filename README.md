# Credit-Card-Transaction-Fraud-Detection

The purpose of this project is to build a fraud detection model to identify credit card transaction frauds in real time. The dataset has ~100,000 records of credit card transactions. Each record contains information like card number, transaction date, merchant information, location information etc.

More than 300 variables (amount variables, frequency variables, day since variables) are created based on the raw data, and 20 variables are selected fpr modeling using filter (KS & FDR) and wrapper (backward stepwise selection) methods. Various supervised machine learning models are then built to identify credit card frauds. Random forest performs better on test dataset than other ML models.

Based on the best fraud detection model, a cost benefit analysis is also conducted to balance true fraud detection gains and false alarm costs.
