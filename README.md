# Analyzing Loan Customers

### Introduction
A bank provides a loan service for property purchases. The customers of this program are the bank's clients. This dataset contains all the personal data of the clients, as well as their credit history over a specific period, and analyzes the behavior of customers who apply for loans to the bank.

Certainly! Below is the overview and description of the dataset, which you can include in a GitHub Markdown document. It provides information about each column in the dataset related to loan applicants.

### Data Overview and Description

| Column               | Description                                                                                          |
|----------------------|------------------------------------------------------------------------------------------------------|
| `loan_id`            | Unique identifier for the loan.                                                                      |
| `birth_date`         | Birth date of the applicant.                                                                         |
| `phone_number`       | Phone number of the applicant.                                                                       |
| `gender`             | Gender of the applicant (e.g., Male, Female).                                                        |
| `married`            | Marital status of the applicant (e.g., Married, Not Married).                                        |
| `dependents`         | Number of dependents relying on the applicant's income.                                              |
| `education`          | Educational background of the applicant.                                                             |
| `self_employed`      | Employment status of the applicant (e.g., Self-Employed, Not Self-Employed).                         |
| `applicant_income`   | Income of the applicant.                                                                             |
| `coapplicant_income` | Income of the coapplicant, if any.                                                                   |
| `loan_amount`        | Amount of loan applied for.                                                                          |
| `loan_term_month`    | Loan term in months.                                                                                 |
| `loan_term_year`     | Loan term in years.                                                                                  |
| `credit_history`     | Credit history of the applicant (e.g., Good, Bad).                                                   |
| `has_credit_card`    | Whether the applicant has a credit card (e.g., Yes, No).                                             |
| `property_type`      | Type of property the loan is intended for (e.g., Apartment, House, Studio).                          |
| `loan_status`        | Status of the loan application (e.g., Approved, Rejected).                                           |

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
