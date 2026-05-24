# Intelligent Coupon Recommendation System

## Project Overview
This project develops a machine learning-powered recommendation and prediction system that determines whether a customer is likely to accept or reject a coupon offer based on demographic, behavioral, and contextual factors.

The project combines:

Data preprocessing
Feature engineering
Imbalanced data handling
Machine learning pipelines
Model comparison and evaluation

The final solution helps businesses improve targeted marketing campaigns and customer engagement through data-driven coupon recommendations.

---

## Business Problem
Businesses frequently send promotional coupons to customers without understanding whether those customers are likely to respond positively.

This leads to:

Low conversion rates
Poor customer engagement
Wasted marketing resources
Inefficient recommendation systems

This project solves the problem by building a predictive machine learning model capable of identifying customers who are more likely to accept coupon recommendations.

---

## Dataset Information
The dataset contains customer demographic and contextual information such as:
- Age
- Occupation
- Income
- Education
- Passenger type
- Marital status
- Weather conditions
- Destination
- Time of day
- Passenger type
- Coupon type
- Restaurant visit frequency
- Coffee house visit frequency
- Bar visit frequency

### Target Variable
- `Y = 1` → Customer accepted the coupon
- `Y = 0` → Customer rejected the coupon

---

## Machine Learning Workflow
The project follows a complete machine learning pipeline:

1. Data Cleaning
   - Removed duplicate records
   - Dropped columns with excessive missing values
   - Handled inconsistent categorical values
3. Missing Value Handling
   - Used SimpleImputer with most_frequent strategy to preserve dataset size.
5. Exploratory Data Analysis (EDA)
6. Feature Engineering
   Several engineered features were created to improve predictive performance.
   Examples:
     - Social lifestyle interaction features
     - Restaurant frequency combinations
     - Time-based features
     - Weather-destination interaction features
     - Income range extraction
     - Expiration conversion to hours
7. Data Transformation
     - One-hot encoding for nominal categorical variables
     - Ordinal encoding for ordered categories
     - Numerical scaling using StandardScaler
8. Imbalanced Data Handling
   Used SMOTE to address class imbalance and improve model learning.
9. Model Training
10. Model Evaluation

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Models
Some models used include:
- Logistic Regression
- Random Forest
- Decision Tree
- XGBoost (optional)
- Gradient Boosting

---

## Evaluation Metrics
The models were evaluated using:
- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Key Insights
- Customer demographics significantly influence coupon acceptance.
- Time and destination affect customer behavior patterns.
- Personalized recommendations improve marketing effectiveness.

---

## Project Outcome
The final model can help businesses:
- improve customer targeting
- increase coupon conversion rates
- reduce marketing waste
- enhance customer experience

## Portfolio Value
This project demonstrates practical skills in:
  - Machine Learning
  - Feature Engineering
  - Recommendation Systems
  - Customer Analytics
  - Predictive Modeling
  - Data Preprocessing Pipelines
  - Business Intelligence
---

## Example Use Cases
This type of system can be applied in:
  - E-commerce platforms
  - Food delivery applications
  - Retail recommendation systems
  - Digital marketing campaigns
  - Customer targeting systems
---

## Future Improvements
- Deploy model using Streamlit
- Build real-time recommendation API
- Improve recommendation personalization
- Experiment with deep learning models
---

## Author
Joshua Udeze

- MBA Finance & Investment | Data Science & Machine Learning Enthusiast
- Email: Udezejoshua@gmail.com
- LinkedIn: www.linkedin.com/in/joshua-udeze-394531154
