Online Payment Analysis (Python)
About This Project

This project is based on online payment data analysis using Python.
The main purpose of this project is to understand different payment methods and analyze their transaction amounts using simple Python concepts.

Dataset Used:

The dataset is stored in a CSV file named:

payment_data.csv

Columns in Dataset:

payment_type – type of payment method

transaction_amount – amount of each transaction

The dataset is manually created for learning and practice.

Tools Used

Python

Pandas

Matplotlib

VS Code / Jupyter Notebook

Step by Step Working of Code
Step 1: Import Libraries

First, required libraries are imported to work with data and graphs.

import pandas as pd
import matplotlib.pyplot as plt

Step 2: Load CSV File

The CSV file is read using pandas and stored in a DataFrame.

df = pd.read_csv("payment_data.csv")

Step 3: Display Full Dataset

The complete dataset is printed in the output so that all records can be seen clearly.

print(df.to_string(index=False))

Step 4: Statistical Analysis

Basic statistical calculations are performed to understand the data better.

Total number of transactions

Total transaction amount

Average transaction amount

Maximum and minimum transaction values

Step 5: Bar Chart

A bar chart is created to show the total transaction amount for each payment method.

This helps in comparing payment methods visually.

Step 6: Pie Chart

A pie chart is created to show the usage distribution of payment methods.

This represents how frequently each payment method is used.

Result

Using this project, we can easily understand:

Which payment method is used more

Which payment method has higher transaction value

Graphs make the analysis easy and clear compared to raw data.

Conclusion

This project helped me understand basic data analysis and visualization using Python.
It is a simple project created for learning purposes and practical understanding of pandas and matplotlib.
