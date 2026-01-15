Amazon Sales Data Preprocessing

Course: Programming for AI (PFAI)
Assignment: Data Preprocessing and Exploratory Analysis

Introduction

This project is based on data preprocessing using an Amazon sales dataset.
The main objective of this assignment is to understand how raw data is cleaned
and prepared before applying any machine learning or artificial intelligence model.

In real-world problems, data is usually incomplete, unclean, and not in a format
that machine learning models can understand directly. Therefore, data preprocessing
is a very important step in any AI pipeline. In this project, I implemented
different preprocessing techniques step by step using a Jupyter Notebook on
Google Colab.

All the code, explanations, and outputs in this repository are written by me
for academic learning purposes.

Why Amazon Sales Dataset?

The Amazon sales dataset contains information related to products, prices,
ratings, and other sales-related features. This dataset represents real-world
e-commerce data, which makes it very useful for learning AI and data science concepts.

I chose this dataset because:

It contains both numerical and categorical data

It reflects real-world business problems

It is suitable for learning preprocessing techniques

It helps understand how AI can be applied to sales data

What is Data Preprocessing?

Data preprocessing is the process of converting raw data into a clean and
usable format. Raw data may contain missing values, text values, different
scales, and noise. If such data is used directly, machine learning models may
give poor results.

Data preprocessing helps to:

Remove missing and invalid values

Convert text data into numerical form

Normalize and scale numerical features

Improve model accuracy and performance

Preprocessing Steps Implemented
1. Loading the Dataset

The dataset was loaded using the pandas library. Pandas makes it easy to work
with rows and columns and perform data analysis operations.

2. Understanding the Dataset

Basic functions like info() and describe() were used to understand:

Column names

Data types

Missing values

Basic statistics

This step helps in planning further preprocessing.

3. Handling Missing Values

Missing values were handled carefully:

Numerical columns were filled using mean values

Categorical columns were filled using the most frequent value

This ensures that no empty values remain in the dataset.

4. Data Type Conversion

Some numerical columns were stored as text (object type). These columns were
converted into numeric format using pandas functions so that mathematical
operations and scaling could be applied correctly.

5. Encoding Categorical Data

Machine learning models cannot understand text values. Therefore, categorical
columns were converted into numerical values using label encoding.

6. Feature Scaling

Numerical features were scaled between 0 and 1 using Min-Max Scaling. This
prevents large values from dominating small values and helps AI models
learn more efficiently.

7. Data Visualization

Simple visualizations were created to understand the distribution of numerical
features. These graphs were saved in the outputs folder for documentation.

8. Saving Cleaned Dataset

After preprocessing, the final cleaned dataset was saved as a CSV file. This
dataset can now be directly used for machine learning or AI models.

Libraries Used

The following Python libraries were used in this project:

pandas

numpy

matplotlib

seaborn

scikit-learn

These libraries are widely used in data science and artificial intelligence projects.

How to Run This Project
Step 1: Open Google Colab

Go to https://colab.research.google.com
 and open the notebook file.

Step 2: Upload Dataset

Upload the Amazon sales dataset CSV file into Google Colab using the file upload
option on the left panel.

Step 3: Run the Notebook

Run each cell one by one. Each cell performs a specific preprocessing step and
shows output below it.

Step 4: Check Outputs

All generated graphs and the cleaned dataset are saved inside the outputs folder.

Project Structure
amazon-sales-preprocessing-pfai/
│
├── amazon_sales_preprocessing.ipynb
│
├── outputs/
│   ├── cleaned_amazon_sales.csv
│   └── visualizations.png
│
└── README.md

Dataset Source

The Amazon sales dataset used in this project was obtained from a publicly
available source (kaggle). Only the raw dataset was used. All preprocessing code,
analysis, explanations, and documentation in this repository are my own work
and were created for academic purposes.

Results and Observations

After preprocessing, the dataset became cleaner and more structured.
Missing values were removed, text data was converted into numeric format,
and numerical features were scaled properly. These steps make the dataset
suitable for training machine learning and AI models.

Conclusion

This project helped me understand the importance of data preprocessing in AI.
I learned that preprocessing is not a single step but a complete pipeline.
Each preprocessing step improves data quality and helps machine learning
models perform better.

This assignment also helped me gain hands-on experience with Google Colab,
pandas, and scikit-learn. In the future, I can apply these preprocessing
techniques to other real-world datasets.

Final Note

This project was completed as part of the Programming for AI (PFAI) course
assignment.
