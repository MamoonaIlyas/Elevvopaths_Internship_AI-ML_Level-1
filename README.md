# Elevvopaths_Internship_AI-ML_Level-1
Task 1: Student Score Prediction  Task 2: Customer Segmentation 

This repository contains the completed projects for Level 1 of the Elvvopath AI/ML Internship. The tasks focus on foundational concepts in machine learning, including supervised and unsupervised learning, data preprocessing, and model evaluation.

Task 1: Student Score Prediction
Objective: To build and evaluate a regression model that predicts student exam scores based on key factors like study hours.

Description:
This project explores the relationship between a student's study habits and their final exam performance. Using a synthetic dataset mimicking the Mall Customer data, I applied various regression techniques to predict a continuous numerical outcome.

Methodology & Key Findings:

Data Preparation: The process began with generating a clean, synthetic dataset, followed by a brief exploratory data analysis (EDA) to visualize the relationship between study hours and exam scores.

Linear Regression: A simple linear regression model was trained using study_hours as a single feature. The model achieved a strong R-squared score, indicating a clear positive correlation between study time and scores.

Model Comparison:

Polynomial Regression: A polynomial model (degree 2) was also implemented to check for non-linear relationships. The results showed that the simple linear model was a slightly better fit for this dataset, suggesting a mostly linear relationship.

Multi-Feature Regression: The model was enhanced by including a second feature, sleep_hours. This multi-feature model achieved the highest R-squared score, demonstrating the importance of including relevant features for improved prediction accuracy.

Tools: Python, Pandas, Matplotlib, Scikit-learn.

Task 2: Customer Segmentation
Objective: To use unsupervised learning to cluster mall customers into distinct segments based on their annual income and spending score.

Description:
This project demonstrates customer segmentation, a core task in marketing analytics. By grouping customers with similar characteristics, businesses can develop more targeted and effective marketing strategies.

Methodology & Key Findings:

Data Preparation: A synthetic dataset was created to simulate mall customer behavior. The key features, Annual Income and Spending Score, were then scaled using StandardScaler to ensure they had an equal impact on the clustering algorithm.

K-Means Clustering:

The Elbow Method was used to determine the optimal number of clusters (k). The analysis clearly pointed to an optimal k of 5.

The K-Means algorithm was then applied with k=5, and the resulting clusters were visualized on a 2D scatter plot.

Cluster Analysis: Each of the five clusters was analyzed based on its average income and spending score, allowing for the creation of meaningful customer profiles, such as "Big Spenders," "Budget Savers," and "Careful Spenders."

Bonus Algorithm: As an extension, the DBSCAN clustering algorithm was also explored. DBSCAN's density-based approach can be effective for finding non-globular clusters and identifying outliers, providing a different perspective on the data's structure.

Tools: Python, Pandas, Matplotlib, Seaborn, Scikit-learn.

Getting Started
To run these projects locally, you will need to have Python and the following libraries installed.

Prerequisites:

Python 3.x

Installation:
You can install all the necessary libraries using pip:

pip install pandas scikit-learn matplotlib seaborn numpy

File Structure
The repository is organized as follows:

.
├── task1_student_score_prediction.py
├── task2_customer_segmentation.py
└── README.md

Conclusion
These two projects provided a solid hands-on experience with both supervised and unsupervised machine learning models. I gained practical experience in data preprocessing, model training, evaluation, and visualization. The tasks were instrumental in building a foundational understanding of how to approach common machine learning problems.
