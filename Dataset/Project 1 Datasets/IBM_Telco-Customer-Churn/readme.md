## About Dataset

### Context
A fictional telco company provided home phone and Internet services to 7043 customers in California during Q3.

### Data Description
- **7043 observations with 33 variables**
- **CustomerID**: Unique identifier for each customer
- **Count**: Used for reporting/dashboarding, sums number of customers in filtered sets
- **Country, State, City, Zip Code**: Customer’s primary residence location details
- **Lat Long, Latitude, Longitude**: Geographical coordinates of customer residence
- **Gender**: Male or Female
- **Senior Citizen**: Whether customer is 65 or older (Yes/No)
- **Partner**: Whether customer has a partner (Yes/No)
- **Dependents**: Whether customer lives with dependents (Yes/No), e.g., children, parents
- **Tenure Months**: Number of months customer has been with company up to the specified quarter
- **Phone Service**: Subscription to home phone service (Yes/No)
- **Multiple Lines**: Subscription to multiple telephone lines (Yes/No)
- **Internet Service**: Type of internet service (No, DSL, Fiber Optic, Cable)
- **Online Security, Online Backup, Device Protection, Tech Support**: Additional subscription services (Yes/No)
- **Streaming TV, Streaming Movies**: Internet streaming of TV or movies (Yes/No, no extra fee)
- **Contract**: Contract type (Month-to-Month, One Year, Two Year)
- **Paperless Billing**: Whether paperless billing is chosen (Yes/No)
- **Payment Method**: Payment type (Bank Withdrawal, Credit Card, Mailed Check)
- **Monthly Charge**: Customer's monthly total charges
- **Total Charges**: Total charges to end of quarter
- **Churn Label and Churn Value**: Indicator if customer left (Yes/1) or stayed (No/0) during the quarter
- **Churn Score**: Score from 0-100 predicting likelihood of churn (higher means more likely)
- **CLTV**: Customer Lifetime Value, predicted with corporate formula (higher means more valuable)
- **Churn Reason**: Specific reason given by customer for leaving

### Source
- Dataset detailed at IBM Community Blog: [Telco Customer Churn](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113)
- Downloaded from IBM Accelerators: [IBM Cognos Analytics](https://community.ibm.com
