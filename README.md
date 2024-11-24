# Customer Bank Churn Analysis

This project analyzes customer churn for a European bank using data from 10,000 customers. The goal is to identify patterns and insights to help the bank improve customer retention.

## Project Overview

The analysis focuses on key factors that influence customer behavior, such as:

- **Credit Score**
- **Account Balance**
- **Product Usage**
- **Geographical Region**
- **Gender**
- **Age**
- **Tenure with the Bank**
- **Estimated Salary**
- **Customer's Credit Card Ownership**
- **Product Engagement**
- **Membership Status**
- **Churn Behavior** (whether the customer has exited)

## Dataset

The dataset contains information from 10,000 customers, with attributes including:

| Column              | Description                                                   |
|---------------------|---------------------------------------------------------------|
| `CustomerId`        | Unique customer identifier                                    |
| `Surname`           | Customer's last name                                          |
| `CreditScore`       | Customer's credit score                                       |
| `Geography`         | Country of residence (e.g., France, Spain, Germany)           |
| `Gender`            | Gender of the customer                                        |
| `Age`               | Age of the customer                                           |
| `Tenure`            | Number of years the customer has been with the bank           |
| `Balance`           | Account balance of the customer                               |
| `NumOfProducts`     | Number of bank products held by the customer                  |
| `HasCrCard`         | Whether the customer owns a credit card                       |
| `IsActiveMember`    | Active membership status                                      |
| `EstimatedSalary`   | Annual estimated salary                                       |
| `Exited`            | Indicates if the customer has churned (1 for yes, 0 for no)   |

## Installation and Requirements

To replicate the analysis, the following packages are required:

- **Python 3.x**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

To install the necessary packages, use the following command:

pip install pandas numpy matplotlib seaborn

🔍 Analysis Steps
Data Loading: The dataset is imported, and initial exploratory analysis is performed.
Data Cleaning: Handling missing values, correcting data types, and merging data from multiple sources.
Exploratory Data Analysis (EDA): Visualization of key features such as credit scores, customer age distribution, account balance, and churn correlations.
Feature Engineering: Creating additional features based on existing data to enhance predictive models.
Modeling (if applicable): Building and evaluating models to predict customer churn.
Results: Summarizing insights and identifying key drivers of churn.
Recommendations: Providing actionable insights to improve customer retention.
📈 Key Findings
The analysis uncovers specific customer segments more likely to churn.
Trends in credit scores, account balances, and product usage provide a clearer picture of factors influencing churn.
The impact of geographical region and age demographics on customer retention is evaluated.
📊 Visualizations
Visualizations used in the analysis include:

Histograms for distributions of customer attributes.
Boxplots for detecting outliers in key variables.
Correlation Heatmaps to identify relationships between variables.
Bar Charts to visualize categorical data such as geographical distribution.
📝 Conclusion
The findings from this analysis can help the bank in understanding which factors significantly contribute to customer churn. Recommendations based on these insights can lead to better customer relationship management and targeted marketing strategies.

📄 License
This project is open-source and available for educational and non-commercial use.

🙏 Acknowledgments

Project inspired by the need to enhance customer retention strategies.
