# FUTURE_ML_02
Task 2-Support Ticket Classification and assign priority levels.

1. Problem Statement
   
Build a Machine Learning model that automatically classifies customer support tickets into categories (Hardware, Access, Miscellaneous, etc.) and assigns priority levels (High / Medium / Low) using NLP techniques.

2. Objective
   
Classify support tickets into predefined categories

Apply NLP preprocessing techniques

Train a machine learning model

Evaluate model performance using metrics

Assign priority levels based on ticket content

3. Technologies Used
   
Python

Pandas

NLTK

Scikit-learn

TF-IDF Vectorization

Logistic Regression

4. Project Workflow
   
Data Preprocessing

Lowercasing

Removing punctuation and numbers

Removing stopwords

Feature Engineering

TF-IDF Vectorization

Model Training

Train-Test Split (80-20)

Logistic Regression

Model Evaluation

Accuracy Score

Classification Report

Confusion Matrix Visualization

5. Model Performance
   
Accuracy: 84.5%

Strong precision and recall across major ticket categories

6. Priority Assignment Logic
   
Rule-based priority assignment:

High → contains words like "urgent", "immediately", "asap"

Medium → contains words like "error", "issue"

Low → general requests

7. Business Insights
   
Automatically routes tickets to correct departments

Assigns priority levels

Reduces manual effort

Improves response time in IT support operations

8. Conclusion
   
This project successfully builds an NLP-based Support Ticket Classification system using TF-IDF and Logistic Regression. The model achieves 84.5% accuracy and demonstrates practical business value by automating ticket categorization and prioritization.
