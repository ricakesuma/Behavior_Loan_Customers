# Analyzing Loan Customers

### Introduction
I conducted an analysis of the behavior and customer profiles at a bank that offers a loan program for property purchases. In this analysis, I will discuss several important aspects related to customer behavior and their profiles. To begin with, it is crucial to understand customer behavior within the context of property loans. I collected data on customers' loan history, including loan status, loan durations, and repayment success rates. This information helps to comprehend customers' payment patterns and predict potential credit risks. Additionally, I analyzed customers' demographic profiles, such as status, income, and occupation. This data is essential as it provides insights into customers' ability to repay loans and their financial risk. For instance, customers with higher incomes may have a better capacity to repay loans compared to those with lower incomes.

### Step-by-Step Analysis:
#### 1. Data Exploration and Preprocessing:
   - **Load the Data**: Read the CSV file containing the customer behavior data.
   - **Data Cleaning**: Handle missing values, duplicate data, outliers, and feature encoding.
   - **Data Transformation**: Transform the data into a suitable format for analysis.

#### 2. Gender-Based Loan Application Analysis:
   - **One-Hot Encoding**: Encode the property types using one-hot encoding.
   - **Grouping by Gender**: Group the data by gender and calculate the sum for each property type.
   - **Visualization**: Create a bar chart to visualize the comparison.

#### 3. Marriage Status and Loan Term Analysis:
   - **Grouping by Marriage Status**: Group the data by marriage status and loan term in years.
   - **Calculate Percentages**: Convert the counts into percentage form.
   - **Visualization**: Create a line chart to visualize the distribution.

### Interpretation:
- **Gender Preference**: Males tend to apply for loans more actively across all property types.
- **Marriage Status Influence**: Married customers are more likely to apply for loans, particularly for longer loan terms.
- **Loan Term Preference**: A 30-year loan term is the most popular, reflecting a preference for long-term loans, likely for substantial purchases like property.
- **Short-Term Loans Less Popular**: Short-term loans are less popular, indicating the bank's clientele leans towards long-term financial commitments.

### Business Recommendations:
- **Targeted Marketing**: Tailor marketing strategies to target males and married customers as they seem to be more engaged in loan applications.
- **Diversified Loan Packages**: Consider offering diversified loan packages that cater to different loan term preferences, with an emphasis on 30-year terms.
- **Customer Education**: Provide educational resources or consultation services to assist customers in understanding loan options that suit their marital status, financial needs, and property preferences.
- **Monitoring and Further Research**: Continuously monitor customer behavior and conduct further research to understand underlying factors influencing these trends, such as income level, occupation, or geographical location.

By understanding the characteristics of the customers who are applying for loans, the bank can create more targeted and effective strategies to cater to their clientele, enhance customer satisfaction, and potentially increase the success rate of loan applications.
