# Predictive Modeling for Loan Default Risk: Unraveling Key Drivers and Enhancing Portfolio Management 
This project illustrates an exploratory data analysis aimed at identifying patterns within a dataset pertaining to clients in banks. The dataset evaluates the clients' capacity to meet their installment payments, decrease loan amounts, and lend at higher interest rates. 
# Introduction 
The following report demonstrates an exploratory data analysis conducted to identify patterns for a dataset for clients in banks. This dataset assesses the client's ability to pay their installments, reduce the loan amount, and lend at higher interest rates. This will also ensure the consumer's ability to repay the loans. The final output of this report is the utilization of the dataset for the portfolio and risk assessment.  

This report is started off with an introduction, and problem statement. Then the data preparation section represents how the data was arranged for analysis. Following the exploratory data analysis section, the report was finalized with derived insights to pinpoint the primary factors influencing loan defaults, along with recommendations for mitigating future occurrences of loan defaults. 
# Problem Statement 
The banking industry is currently facing challenges of efficiently identifying clients who have the risk of defaulting on loans. To address this problem, it is crucial for banks to identify factors behind loan default. To mitigate possible impacts on banks, it is crucial to understand key variables, develop actionable insights, and ensure retaining of creditworthy applicants. 
# Data Preparation 
Data preparation for the given dataset was started with data cleaning. This step is crucial when ensuring the integrity and quality of the dataset. The data cleaning was conducted to ensure data that is used for analysis is complete and does not have any missing values. 
In the pandas library, the following methods were used to identify the first few rows, get basic statistics, and check missing values.  The data analysis section presents an introduction about data analysis and exploratory data analysis for the utilized banking dataset. After the exploratory data analysis, the report was concluded by giving mitigation strategies for the loan default. 

![Figure 1](https://github.com/anushanga2/bank-dataset/blob/main/images/1.PNG)  

Then the rows with missing values and duplicated rows were adjusted. Finally, the data with correct data types were checked to ensure they are in the right data format. 

![Figure 2](https://github.com/anushanga2/bank-dataset/blob/main/images/2.PNG)  

Figure 2: Data Preparation 2 

# Data Analysis 
In the data analysis section, the cleaned dataset was utilized to understand multifaceted factors that contribute to loan default. Using python pandas library, an exploratory data analysis (EDA) was conducted to clean, preprocess, and analyze the data. The dataset included a range of information from client’s financial histories to loan performance metrics, with each variable holding the potential to unveil patterns that could be instrumental in risk assessment and portfolio management. Through these stages, a basis for a deeper exploration into predictive modeling is conducted seeking to identify key drivers that will empower the banking institutions in making informed decisions, mitigate risks and optimize lending practices. 

# Exploratory Data Analysis (EDA) 
## Histrograms 

![Histrogram for the goods price](https://github.com/anushanga2/bank-dataset/blob/main/images/1.png?raw=true)  

Figure 3: Histrogram for goods price  

The following histograms represent the number of occurrences for different values in a dataset. 

![Histrogram for the credit amount](https://github.com/anushanga2/bank-dataset/blob/main/images/3.png?raw=true)  

Figure 4: Histrogram for credit amount 


![Histrogram for the annuity amount](https://github.com/anushanga2/bank-dataset/blob/main/images/4.png?raw=true)  

Figure 5: Histrogram for the annuity amount  

## Distribution of the target variable

![Distribution of the loan default status](https://github.com/anushanga2/bank-dataset/blob/main/images/5.png?raw=true) 

Figure 6: Distribution of the loan default status  

The target variable in this dataset describes the patterns of difficulties in paying installments and risk assessment of the loan default based on binary variables. The ‘1’ indicates that the client has defaulted on their loan, and ‘0’ indicates the client has not defaulted. The target variable is a focal point for predictive modeling and risk assessment. The main aim of this pattern is to predict the likelihood of loan default for new applicants which will benefit the institutions about loan approvals and risk management. The above chart represents that around 282,686 clients have not defaulted and around 24,825 clients have defaulted on their loans. 

## % of customers with at least one late payment 

![Figure 7: Distribution of percentage of customers with late payments](https://github.com/anushanga2/bank-dataset/blob/main/images/6.png)  

Figure 7: Distribution of percentage of customers with late payments  

The above chart represents that around 8.1% of clients have made late payments out of all the clients.  91.9% of customers have consistently met the payment deadlines showing a strong financial ability. 

## Types of loans the bank provides and the percentage of missed payments 

![Figure 8: Percentage of missed payment by loan type](https://github.com/anushanga2/bank-dataset/blob/main/images/7.png?raw=true) 

Figure 8: Percentage of missed payment by loan type  

Out of the contract types most of the loans are cash loans which accounts for 278,232 compared with revolving loans which is 29,279. Cash loans are typically for short-term financial needs, such as unexpected expenses. Revolving loans are basically from credit cards which allow borrowers to borrow and repay over time. The missed payment percentage of cash loans accounts for 8.34% and revolving loans missed payment percentage is only 5.47%. 

## Gender Distribution among clients 

![Figure 9: Gender distribution among clients](https://github.com/anushanga2/bank-dataset/blob/main/images/8.png)  

Figure 9: Gender distribution among clients  

Out of all the clients, 65.8% are females and 34.2% are Male. The average income levels of males accounts for 193,396 and average income levels of females are 156,032. 


## Occurrences of Missed Payments by gender 

![Figure 10: Occurrences of missed payments by the gender ](https://github.com/anushanga2/bank-dataset/blob/main/images/9.png)  

Figure 10: Occurrences of missed payments by the gender  

![Figure 11: Percentage of missed payments for male and female customers   ](https://github.com/anushanga2/bank-dataset/blob/main/images/15.png)  
![Figure 11: Percentage of missed payments for male and female customers   ](https://github.com/anushanga2/bank-dataset/blob/main/images/161.png)  

Figure 11: Percentage of missed payments for male and female customers  

Out of all the occurrences, the majority of males have encountered a payment difficulty than men. Out of the males 10% have missed the payments and defaulted. Out of females only 7% have missed the payments and defaulted. 

![Figure 12: Gender, income level and missed payments ](https://github.com/anushanga2/bank-dataset/blob/main/images/18.png?raw=true)  

Figure 12: Gender, income level and missed payments  

This chart shows that clients with minimum income range have shown the highest missed payment percentage.  

## Family Status and gender distribution 
![Figure 13: Family Status and gender distribution](https://github.com/anushanga2/bank-dataset/blob/main/images/10.png)  

Figure 13: Family status and gender distribution  

Out of different gender distributions, most males and females are married. Window men and women represent the lowest table. It can also be identified that married males and females have the highest annuity to income ratio of 19%.  

## Comparison of average total income and loan default 
![Figure 14: Comparison of total income and loan default](https://github.com/anushanga2/bank-dataset/blob/main/images/11.png?raw=true)  

Figure 14: Comparison of total income and loan default  

When comparing the average total income levels, the defaulted clients show a slightly lesser income level than those who have not defaulted. 

## Comparison of average annuity payment and loan default 
![Figure 15: Comparison of average annuity payments and loan default](https://github.com/anushanga2/bank-dataset/blob/main/images/12.png?raw=true)  

Figure 15: Comparison of average annuity payments and loan default  

When comparing the average annuity payments, it can be identified that the defaulted loan holders have slightly lesser average payment than those who have not defaulted. 

## Correlation Heat map for Annuity, Income, Credit and, Loan Default 

The following heatmap shows that the Annuity and credit levels have the highest positive correlation level. Amount of total income and credit level has a medium positive relationship. The amount of total income and annuity also has a medium positive relationship. However, there is no/ minimum correlation between the target, annuity, income and credit levels. 
![Figure 16: Correlation heat map for annuity, income credit and loan default](https://github.com/anushanga2/bank-dataset/blob/main/images/13.png)  

Figure 16: Correlation heat map for annuity, income credit and loan default  

## Distribution of missed payments by age group
When considering the age group against distribution of missed payments, 30-39 age category shows the highest amount of missed payments. The second most age group that missed the payments and defaulted are the 20-29 group. 
![Figure 17: Distribution of missed payments by age group](https://github.com/anushanga2/bank-dataset/blob/main/images/14.png)  

Figure 17: Distribution of missed payments by age group  

# Conclusion 

From the above analysis, the main factors that affect the loan default were identified. One is the higher annuity-to-income ratio, where individuals with higher annuity payments with respect to their income have a higher chance of defaulting on their loans. Another aspect is the age and income level. The clients with age categories 30-35, 40-49, and 50-55 have the highest frequency of missed payments. Also, when the client's income level is low, there is a high chance of defaulting on the loan. When considering marital status, married people showed a high likelihood of missing payments, and cash loans were the most highly defaulted loan type.  

To mitigate loan default strategies, banks must follow several strategies. The first one is to conduct income verification and affordability assessments. This will ensure the clients are only allowed to take loans based on what they are eligible for. The second step is to conduct loan purpose restrictions. Since cash loans have high default rates, banks can prioritize the loans based on purpose. The third option is to ensure flexible repayment options, such as allowing loan repayment levels to match the borrower's payment capacity. These strategies will benefit the bank's future risk mitigation strategy and ultimately enhance profitability.


