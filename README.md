# Credit Card Exploratory Data Analysis (EDA)

**Project Overview**

This project focuses on exploratory data analysis (EDA) for a bank's credit card department. The aim is to assist the bank in determining:

* How to approve or reject loan applications.
* To whom loans should be provided.
* Risk assessment strategies for loan approvals, balancing business opportunities and financial risks.

**Objectives**

1. Analyse applicant profiles to determine loan approval eligibility.
2. Understand the factors influencing loan repayment and default likelihood.
3. Provide actionable insights for targeted sales and operational focus.

**Datasets**

The analysis is based on the following datasets:
1. Application Data: Client information at the time of loan application, including payment difficulties.
2. Previous Application Data: Historical loan data, including approval status (Approved, Cancelled, Refused, Unused offer).
3. Columns Description: Data dictionary describing variable meanings.

**Data Cleaning**

1. Handling Missing Values:
    * Drop columns with >40% missing values.
    * Impute remaining missing values using mean, median, or mode.
2. Fixing Data Issues:
    * Correct invalid data types.
    * Address negative values in columns like Date and Age.
    * Identify and treat outliers if necessary.

**Analysis Workflow**

1. Data Preparation:
    * Bin categorical columns.
    * Visualise and plot key variables.
    * Remove irrelevant columns.
2. Data Imbalance:
    * Check and analyse data distribution.
3. Univariate, Bivariate, and Multivariate Analysis:
    * Explore relationships between variables.
    * Identify correlations.
4. Merging Datasets:
    * Combine Application Data and Previous Application Data by their common ID.
    * Perform comprehensive analysis on merged data.

**Key Features**

* Risk profiling for loan approval.
* Insights into client demographics and historical loan behaviour.
* Visualisation-driven insights for better decision-making.

**Tools and Technologies**

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Jupyter Notebook

**Results and Insights**

* Identification of key factors influencing loan approvals.
* Recommendations for targeting high-potential clients.
* Data-driven strategies for minimising financial risks.
