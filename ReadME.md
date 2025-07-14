📊 Banking Data Analysis with Python and MySQL
🔍 Project Overview
This project performs a comprehensive exploratory data analysis (EDA) on customer banking data stored in a MySQL database. Using Python libraries such as Pandas, Matplotlib, and Seaborn, the script connects to the database, extracts data, and generates statistical summaries and insightful visualizations.

🛠️ Tools & Technologies Used
Python 3

MySQL (as the backend database)

MySQL Connector for Python

Pandas for data manipulation

Matplotlib & Seaborn for visualization

NumPy for numerical operations

🗂️ Dataset
The analysis is performed on the customer table from the banking_ana database. It contains various customer attributes such as:

Demographics (e.g., Gender, Nationality)

Financial Metrics (e.g., Estimated Income, Loans, Credit Balance)

Behavior Insights (e.g., Number of Credit Cards, Occupation)

📌 Key Steps Performed
1. Database Connection & Data Loading
python
Copy
Edit
mysql.connector.connect(host="localhost", user="root", password="", database="banking_ana")
SQL query executed to fetch all records from the customer table into a Pandas DataFrame.

2. Data Exploration
.head(), .info(), .shape() to understand structure and data types.

.describe() to generate summary statistics for numerical columns.

3. Feature Engineering
Created a new column Income Band by binning Estimated Income into categories: low, med, high.

4. Univariate Analysis
Categorical Columns: Count plots using Seaborn to visualize distributions.

Numerical Columns: Histograms with KDE (Kernel Density Estimation) for a smooth curve representation.

5. Bivariate Analysis
Count plots grouped by:

GenderId and

Nationality

To examine interaction effects between categorical variables.

6. Heatmap (Correlation Matrix)
Plotted heatmap of correlation values between key numerical columns to identify multicollinearity or relationships.

📈 Visualizations Generated
Bar plots for value counts

Histograms for numerical attributes

Countplots with hue for categorical comparisons

Correlation heatmap

##Download_video : https://github.com/SuryaPavan-001/Banking_End_to_End_Data_Analysis/blob/main/Video_Sample/Dashboard_video.mp4 

