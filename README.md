## Information
Written by: Brandon Welsh

Start date: 3/13/2024 9:00pm

Due date: 3/18/2024 11:59pm

## Program Goals
"You work at a company that specializes in student loan refinancing. If the company can predict whether a borrower will repay their loan, it can provide a more accurate interest rate for the borrower. Your team has asked you to create a model to predict student loan repayment.

The business team has given you a CSV file that contains information about previous student loan recipients. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loans. The CSV file contains information about these students, such as their credit ranking." 

(copied from BootcampSpot Module 18 Challenge Overview)

## Dependencies
pandas, tensorflow, sklearn

## Setup Instructions
Run pip install pandas, tensorflow and sklearn before running program (if you do not already have these libraries).

Next, run the following:

    import pandas as pd
    import tensorflow as tf
    from tensorflow.keras.layers import Dense
    from tensorflow.keras.models import Sequential
    from sklearn.model_selection import train_test_split
    from sklearn.preprocessing import StandardScaler
    from sklearn.metrics import classification_report
    from pathlib import Path

## How to use
Run each jupyter notebook cell. That's pretty much it.

## Resources Utilized
This section is dedicated to keep track of what I used to help complete this project:

## Bugs

## Update Log
3/13/2024: Created github repo, took a look at the challenge.

3/14/2024: Completed Steps 1-4 (data preprocessing)