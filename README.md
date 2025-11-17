Bank Churn Analysis

This project analyzes customer churn in a European bank using a dataset containing account information for 10,000 customers. The analysis is implemented in Google Colab and explores patterns, demographics, and segments that influence churn behavior.

📌 Objective

The main goals of this analysis are:

Identify attributes that are more common among churners compared to non-churners.
Determine whether churn can be predicted using available customer variables.
Explore the overall demographics of the bank's customers.
Examine differences in account behavior among German, French, and Spanish customers.
Segment the customer base based on behavior and demographic characteristics.

🛠 Dataset

The dataset contains the following fields:
CustomerID
CreditScore
Geography (Germany, France, Spain)
Gender
Age
Tenure
Balance
NumberOfProducts
HasCrCard
IsActiveMember
EstimatedSalary
Exited (Churn indicator)

📊 Key Analysis Questions

Attributes more common among churners:
Compare metrics such as age, balance, credit score, and product usage between churners and non-churners.

Churn prediction:
Investigate correlations and patterns that can help predict customer churn using features in the dataset.

Customer demographics:
Analyze the overall demographic profile including age distribution, gender, geography, and account tenure.

Country-specific account behavior:
Explore differences among German, French, and Spanish customers in terms of account activity and balance.

Customer segmentation:
Identify distinct segments within the bank's customer base using clustering or categorization based on account behavior and demographics.

📂 How to Use
Open Google Colab
Upload Bank_Churn_Analysis.ipynb or open it from GitHub.
Run each cell sequentially to reproduce the analysis.
Explore visualizations and insights generated for churn prediction and customer segmentation.

🛠 Tools & Libraries

Python 3.x
Pandas, NumPy (Data manipulation)
Matplotlib, Seaborn (Visualization)

📈 Outcome

By completing this analysis, users can:
Identify key characteristics of churn-prone customers.
Understand demographic patterns across different countries.
Discover actionable segments for targeted retention strategies.
