# 📊 Case Study: Exploratory Data Analysis in Risk Analytics for Banking and Financial Services

## 🏦 Business Understanding (Given P.S)

Lending money is a high-stakes game, especially when dealing with clients with insufficient or non-existent credit histories. This makes it challenging for loan-providing companies to make informed decisions, as some consumers may default due to the lack of historical data on their creditworthiness. As a data analyst working for a consumer finance company that specializes in urban customer loans, your task is to utilize Exploratory Data Analysis (EDA) to unearth patterns in the data. This will help ensure that capable applicants are not unjustly rejected.

### Key Risks for the Company:
1. **Loss of Business**: Not approving a loan to a likely repayer results in a missed business opportunity.
2. **Financial Loss**: Approving a loan to a potential defaulter leads to financial losses.

### Data Scenarios:
- **Clients with Payment Difficulties**: These clients had late payments exceeding X days on at least one of the first Y installments.
- **Other Clients**: Clients who paid on time.

### Possible Company Decisions:
1. **Approved**: Loan application is approved.
2. **Cancelled**: The client cancels the application during the approval process.
3. **Refused**: The company rejects the loan application.
4. **Unused Offer**: The loan is cancelled by the client at various stages of the process.

## 🎯 Business Objectives

The goal is to identify patterns indicating a client's difficulty in paying installments. These insights will help in making informed decisions such as denying loans, reducing loan amounts, or lending to risky applicants at higher interest rates. Ultimately, this ensures that capable consumers are not rejected, and the company minimizes its risk.

In summary, we aim to understand the driving factors behind loan default, leveraging this knowledge for better portfolio and risk assessment.

## 🗂️ Data Understanding

### 1. `application_data.csv`
This dataset contains all the client information at the time of loan application, detailing whether the client has payment difficulties.

### 2. `previous_application.csv`
This dataset provides information on the client's previous loan applications, indicating whether the previous applications were approved, cancelled, refused, or unused offers.

### 3. `columns_description.csv`
This data dictionary explains the meaning of the variables in the datasets.

## 🔍 Next Steps

1. **Load and Explore the Data**: Understand the structure and content of each dataset.
2. **Data Cleaning and Preprocessing**: Handle missing values, outliers, and inconsistent data.
3. **Exploratory Data Analysis (EDA)**: Visualize and analyze the data to identify key patterns and correlations.
4. **Feature Selection**: Identify the most relevant variables that indicate loan default.
5. **Insights and Recommendations**: Provide actionable insights based on the analysis.

By following these steps, we will be able to provide valuable insights that can help the company in making informed lending decisions, thus minimizing risk and maximizing profit. 📈💡
 
