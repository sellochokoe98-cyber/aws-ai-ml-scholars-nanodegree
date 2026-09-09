# NumPy Mean Normalization and Data Separation

## Project Overview

This project is a beginner-level NumPy exercise focused on **mean normalization** and **data separation**.

The lab demonstrates how to create a dataset using NumPy, calculate the mean and standard deviation, normalize the data, and split the dataset into training, cross-validation, and test sets.

## Tools Used

* Python
* NumPy
* Jupyter Notebook

## What I Learned

In this lab, I learned how to:

* Create a NumPy array with random data
* Check the shape of an array
* Calculate the mean of each column
* Calculate the standard deviation of each column
* Apply mean normalization
* Create random row indices
* Split data into different datasets
* Check the shape of the resulting datasets

## Dataset

A random dataset containing:

* **1,000 rows**
* **20 columns**
* Random integer values from **0 to 5,000**

The original dataset has the shape:

text
(1000, 20)


## Mean Normalization

Mean normalization was performed using the following formula:

python
X_norm = (X - ave_cols) / std_cols


The normalized data should have an overall mean very close to **0**.

## Data Separation

The normalized dataset was randomly separated into three sets:

| Dataset              | Percentage | Rows |
| -------------------- | ---------: | ---: |
| Training Set         |        60% |  600 |
| Cross Validation Set |        20% |  200 |
| Test Set             |        20% |  200 |

The final shapes are:

text
Training Set:       (600, 20)
Cross Validation:   (200, 20)
Test Set:           (200, 20)

## Project Structure

text
numpy-mean-normalization/
│
├── README.md
└── mean_normalization.ipynb
```

## Conclusion

This exercise helped me understand some basic data preprocessing steps used in machine learning. Mean normalization puts numerical features on a similar scale, while separating the data allows it to be used for training, validation, and testing.

## Skills Demonstrated

**Python | NumPy | Data Preprocessing | Jupyter Notebook | Machine Learning Fundamentals**

