📊 Loan Approval Analysis – EDA & Data Cleaning
📌 Overview
This project focuses on performing exploratory data analysis (EDA) and data preprocessing on a loan approval dataset to understand the key factors influencing loan approval decisions.
The analysis includes handling missing values, addressing skewness, validating insights, and ensuring the reliability of results through comparison before and after data cleaning.

🎯 Objectives


Understand the structure and quality of the dataset


Identify and handle missing values


Analyze relationships between features and loan approval


Handle skewed numerical data and outliers


Validate insights before and after data cleaning



🗂️ Dataset Description
The dataset contains information about loan applicants, including:


Gender


Married


Dependents


Education


Self_Employed


ApplicantIncome


CoapplicantIncome


LoanAmount


Loan_Amount_Term


Credit_History


Property_Area


Loan_Status



🔍 Exploratory Data Analysis
Initial exploration was performed to understand:


Data types and structure


Missing values across features


Distribution of numerical variables


Relationships between categorical features and loan approval


Key observations:


Missing values were present in multiple features


Numerical features such as LoanAmount and Income were highly skewed


Credit History showed a strong relationship with loan approval



🧹 Data Cleaning & Preprocessing
Handling Missing Values


Categorical features were imputed using mode


Numerical features were imputed using median to reduce the impact of skewness


Handling Skewness


Numerical features such as LoanAmount, ApplicantIncome, and CoapplicantIncome were highly skewed


Log transformation was applied to normalize distributions


Outlier Handling


Outliers were identified in financial variables


Instead of removing them, their impact was reduced using log transformation to preserve meaningful data



📊 Key Insights
Credit History
Credit History is the most influential factor in loan approval. Applicants with a positive credit history have significantly higher approval rates compared to those without it.
Gender
Loan approval rates for male and female applicants are very similar, indicating minimal impact of gender on loan approval decisions.
Property Area
Property Area shows moderate variation in approval rates, suggesting a slight influence based on location.
Income & Loan Amount
Income and Loan Amount contribute to loan approval decisions, but their impact is secondary compared to credit history.

🔄 Validation of Insights
The analysis was performed before and after data cleaning to ensure reliability.


Only minor variations in approval rates were observed


Overall patterns remained consistent


Credit History continued to show strong influence


Gender remained a weak factor


This confirms that the insights are stable and not significantly affected by missing values or inconsistencies.

🧠 Final Conclusion
Credit History is the primary determinant of loan approval decisions, significantly outweighing demographic and income-related factors.
Income and Loan Amount play a supporting role, while demographic attributes such as Gender have minimal influence.
The consistency of results before and after data cleaning confirms that the insights are reliable and suitable for real-world decision-making.

🛠️ Tools & Technologies


Python


Pandas


NumPy


Matplotlib



🚀 Key Learnings


Importance of handling missing data correctly


Understanding skewness and applying appropriate transformations


Avoiding blind removal of outliers in financial datasets


Validating insights to ensure reliability



📌 Future Improvements


Build predictive models for loan approval


Perform feature importance analysis


Explore advanced techniques for handling imbalance



👤 Author
Pavan Kalyan Kasipaka





If you want next:
👉 I can help you with resume bullet points + interview questions based on this project 🚀
