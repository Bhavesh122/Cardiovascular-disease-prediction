Cardiovascular Disease Prediction

This repository contains a project to predict the likelihood of cardiovascular disease based on various features. The prediction model is built using machine learning techniques, and the project includes data preprocessing, feature engineering, model training, and evaluation.

Features

Preprocessing:

Removed null values (if any) using methods like replacing with mean, median, or mode, or dropping rows/columns.

Converted age from days to years for better interpretability.

Feature Engineering:

Checked for null values in the dataset.

Created age_years by converting age from days to years and dropped the original age column.

Visualization:

Target Variable Distribution: Displayed the distribution of individuals with and without cardiovascular disease.

Age Group Analysis: Categorized individuals into age groups (Young: 29-50, Middle: 50-63, Old: 63+), visualized with pie charts, and displayed group sizes.

Machine Learning Models:

Logistic Regression

Random Forest Classifier

Support Vector Machine

k-Nearest Neighbors (KNN)

XGBoost

Decision Tree Classifier

Neural Network

Best Performing Model:

Random Forest Classifier achieved the highest accuracy of 73.14%.

Prediction:

Used the trained models to predict cardiovascular disease based on user input.

Factors Considered

The dataset includes the following factors for predicting cardiovascular disease:

age: Age of the individual (converted from days to years).

gender: Gender of the individual.

height: Height in cm.

weight: Weight in kg.

ap_hi: Systolic blood pressure.

ap_lo: Diastolic blood pressure.

cholesterol: Cholesterol level (1: normal, 2: above normal, 3: well above normal).

gluc: Glucose level (1: normal, 2: above normal, 3: well above normal).

smoke: Smoking status (1: smoker, 0: non-smoker).

alco: Alcohol consumption (1: consumer, 0: non-consumer).

active: Physical activity status (1: active, 0: inactive).

cardio: Presence of cardiovascular disease (1: has disease, 0: no disease).

Repository Structure

app.py: Python script for the web application.

form.html: HTML form for user input.

result.html: HTML page to display predictions.

styles.css: Stylesheet for the web application.

background.jpg: Background image used in the web interface.

Jupyter Notebook: Contains data analysis, preprocessing, feature engineering, and model training.

Installation

Clone the repository:

git clone https://github.com/Bhavesh122/Cardiovascular-disease-prediction.git

Install dependencies:

pip install -r requirements.txt

Usage

Run the web application:

python app.py

Open the application in your web browser at http://localhost:5000.

Input user details to predict the likelihood of cardiovascular disease.

Visualization Examples

Target Variable Distribution

A bar chart showing the distribution of individuals with and without cardiovascular disease.

Age Group Analysis

Pie chart representation of age groups categorized as Young, Middle, and Old.

Results

The Random Forest Classifier achieved the best accuracy of 73.14%, making it the most reliable model for prediction.

Contributing

Contributions are welcome! Please fork the repository and create a pull request.

License

This project is licensed under the MIT License.

Acknowledgments

Libraries used: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost.

Thanks to the open-source community for their tools and support.

