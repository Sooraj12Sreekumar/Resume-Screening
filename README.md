# Resume-Screening

This project focuses on automating the resume screening process using Machine Learning (ML) techniques. Resume screening is a critical task for companies that receive a large number of job applications. This tool helps in efficiently shortlisting candidates whose resumes match the required skills and experience, leveraging ML algorithms to streamline the hiring process.

## Features

1.Data Loading and Preprocessing:

- Loads the dataset containing resume text and their respective categories.

- Performs text cleaning, tokenization, and stemming/lemmatization.

2.Exploratory Data Analysis (EDA):

- Visualizes the distribution of resume categories using count plots.

- Analyzes the frequency of each job category.

3.Feature Extraction:

- Uses TF-IDF (Term Frequency-Inverse Document Frequency) to convert text data into numerical features.

- Model Training and Evaluation:

4.Implements multiple ML algorithms including:

- Support Vector Machine (SVC)

- Random Forest

- Multinomial Naive Bayes

- Logistic Regression

- K-Nearest Neighbors (KNN)

- Evaluates models using metrics like accuracy, precision, recall, and F1-score.

5.Visualization of Results:

- Generates confusion matrices and classification reports for model performance analysis.

## Dataset
The dataset consists of 962 resumes labeled into 25 unique categories such as:

- Data Science

- HR

- Web Designing

- Mechanical Engineer

- Java Developer

and more...

Each entry includes:

- Category: The job category of the resume.

- Resume: The text content of the resume.

## Prerequisites:
- Python 3.x

- Jupyter Notebook

- Required libraries: pandas, numpy, seaborn, matplotlib, nltk, scikit-learn

## Results
The project evaluates multiple ML models and provides insights into their performance. For example:

- Random Forest achieved the highest accuracy of 90%.

- Logistic Regression showed the best balance between precision and recall.

Visualizations such as count plots and confusion matrices help in understanding the distribution of categories and model performance.
