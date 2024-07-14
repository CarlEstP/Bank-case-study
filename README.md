## 1. Stack Data & Analyst

- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Plotly

## 2. Purpose of the Challenge

The purpose of this challenge is to put into practice the knowledge of:

- Exploratory Data Analysis (EDA)
- Data cleaning
- Handling missing data
- Data visualization
- Justifying conclusions based on the proposed case

## 3. Context of the Case, Purpose, and Datasets

We are provided with data extracted from marketing campaigns of a Portuguese banking institution. These campaigns were based on telephone calls, often requiring multiple contacts with the same client to determine if the term deposit product would be subscribed or not.

After analyzing the datasets, the goal is to answer: Has this campaign been effective in gaining subscriptions to financial products from the banking institution?

Two datasets are provided:

### First Dataset ('bank-additional.csv')

Columns include:

- **age**: Client's age.
- **job**: Client's occupation or profession.
- **marital**: Client's marital status.
- **education**: Client's educational level.
- **default**: Indicates if the client has a history of credit default (1: Yes, 0: No).
- **housing**: Indicates if the client has a housing loan (1: Yes, 0: No).
- **loan**: Indicates if the client has any other loan (1: Yes, 0: No).
- **contact**: Method of contact used to communicate with the client.
- **duration**: Duration in seconds of the last interaction with the client.
- **campaign**: Number of contacts made during this campaign for this client.
- **pdays**: Number of days that have passed since the last contact with the client during this campaign.
- **previous**: Number of times the client was contacted before this campaign.
- **poutcome**: Outcome of the previous marketing campaign.
- **emp.var.rate**: Employment variation rate.
- **cons.price.idx**: Consumer price index.
- **cons.conf.idx**: Consumer confidence index.
- **euribor3m**: Three-month Euribor interest rate.
- **nr.employed**: Number of employees.
- **y**: Indicates if the client has subscribed to a product or service (Yes/No).
- **date**: Date of the interaction with the client.
- **contact_month**: Month of the interaction with the client during the marketing campaign.
- **contact_year**: Year of the interaction with the client during the marketing campaign.
- **id\_**: Unique identifier for each record in the dataset.

### Second Dataset ('customer-details.xlsx')

This Excel provides information on demographic characteristics and buying behavior of bank clients. It consists of three different worksheets, each containing clients who entered the bank in different years.
Columns include:

- **Income**: Annual income of the client in monetary terms.
- **Kidhome**: Number of children in the client's household.
- **Teenhome**: Number of teenagers in the client's household.
- **Dt_Customer**: Date when the client became a customer of the company.
- **NumWebVisitsMonth**: Number of monthly visits by the client to the company's website.
- **ID**: Unique identifier of the client.
