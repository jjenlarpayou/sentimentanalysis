# Sentimentanalysis

## Overview
<p>This project centers on sentiment analysis of the "Amazon Fine Food Reviews" dataset, a vast
collection of reviews for fine foods on Amazon spanning a decade, from October 1999 to October
2012. This dataset comprises roughly 568,454 reviews contributed by 256,059 users for 74,258
distinct food products. The project's primary objective is to ascertain the sentiment (positive or
negative) expressed in these reviews. The project will establish a distributed computing
environment for managing big data and machine learning workloads using Hadoop and Spark. <b>Note: </b> This project runs on Google Cloud Platform installing Hadoop, Spark, and Jupyter notebook</p>

## How to Run the Project
The project used crack surface from https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews/data. This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.
**Data includes:**
- Reviews from Oct 1999 - Oct 2012
- 568,454 reviews
- 256,059 users
- 74,258 products
- 260 users with > 50 reviews

### Prerequisites
#### **1. Required Software**
- **Python 3.x** ([Download Here](https://www.python.org/downloads/))
- **Google Cloud Platform**
- **Apache Spark**
- **Hadoop (HDFS)**
- **Java 8 or later** (Required for Spark)
- **Matplotlib & Seaborn**
- **NumPy & Pandas**
- **PySpark**

## Key Features
- Data Imputation
- Exploratory Data Analysis (EDA)
- Text Processing: Tokenizer, StopWordsRemover, HashingTF, and Inverse Document Frequency

### Model used
- Naive Bayes
- Logistic Regression
- Decision Tree
- Random Forest

## Result

### Naive Bayes
- Accuracy: 81.404
- Precision: 82.72
- Recall: 81.40
- F1-score: 81.91
- AUC: 84.39
<div align="center"><img width="400" alt="image" src="https://github.com/user-attachments/assets/e7f7f999-4612-4920-9417-3cea91130b8f" />
</div>
<div align="center"><b>Figure 1: </b>Confusion matrix for Naive Bayes</div>

### Logistic Regression
- Accuracy: 84.39
- Precision: 83.74
- Recall: 84.39
- F1-Score: 83.94
- AUC: 84.99
<div align="center"><img width="400" alt="image" src="https://github.com/user-attachments/assets/0e3bb3e4-0c09-4dc8-9d8f-8d3d728e71dc" />
</div>
<div align="center"><b>Figure 2: </b>Confusion matrix for Logistic Regression</div>

### Decision Tree
- Accuracy: 78.10
- Precision: 74.86
- Recall: 78.10
- F1-Score: 74.20
- AUC: 72.03
<div align="center"><img width="400" alt="image" src="https://github.com/user-attachments/assets/81c8e0ae-1357-4461-9b68-534c4567bafe" />
</div>
<div align="center"><b>Figure 3: </b>Confusion matrix for Decision Tree</div>

### Random Forest
- Accuracy: 76.81
- Precision: 82.19
- Recall: 76.81
- F1-Score: 66.77
- AUC: 83.16
<div align="center"><img width="400" alt="image" src="https://github.com/user-attachments/assets/572db78f-82bd-4137-b674-b9a1677b8500" />
</div>
<div align="center"><b>Figure 3: </b>Confusion matrix for Random Forest</div>
