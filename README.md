# Bank-Campaign-Analysis-PowerBi

## Bank Marketing Campaign Analysis: 
The Bank conducted a marketing campaign for one of its financial products ‘Term Deposits’. This campaign data contains information about all the customers who were contacted during a 
particular duration to subscribe their product Term Deposits.

### Term Deposit: 
A term deposit, also known as a fixed deposit or time deposit, is a financial arrangement where an individual or institution deposits a specific amount of money with a bank or financial institution for a predetermined period, typically at a fixed interest rate. The funds are inaccessible for the agreed-upon term, providing a secure and usually higher interest-earning investment.

Attributes/ columns in this dataset are:

customers data:

1 - age: (numeric)

2 - job: type of job

3 - marital: marital status 

4 - education: (categorical: primary, secondary, tertiary and unknown)

5 - default: has credit in default? (categorical: 'no','yes','unknown')

6 - housing: has housing loan? (categorical: 'no','yes','unknown')

7 - loan: has personal loan? (categorical: 'no','yes','unknown')

8 - balance: Balance of the individual

current campaign:

9 - contact: contact communication type (categorical: 'cellular','telephone')

10 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')

11 - day: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')

12 - duration: last contact duration, in seconds

 other attributes:
 
13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

14 - pdays: number of days that passed by after the client was last contacted from a previous campaign 

15 - previous: number of contacts performed before this campaign and for this client 

16 - poutcome: outcome of the previous marketing campaign 

17 - deposit: it is the output/ target variable, which contains information about whether the customer has subscribed the product or no in ( yes or no form) 


### The key isights from this analysis were:
1. " 47 % " of customers has subscribed to the Term Deposit out of total customers contacted during the campaign.
2. " 45% "of customers out of total opening term deposit are Senior aged people above 60+ age. Senior aged are the ones with highest bank balance among all other age groups. Focusing more on this age group in 
   next campaign will increase the subscription rate.
3. Single marital status people are more interested in this product followed by Divorsed people. Married ones are the least.
4. The more the No of times contacted the same customer during campaign,the more likely he or she will decline to open a term deposit. So thats why no of contacts should be reduced to less than 3 in order to
   save time and effort in contacting new customers. 
5. Customers having personal loan and house loan show less interest toward term deposit.
6. Occupation wise retired personal,self employed customers are high balance holders. But retired and students are more interested in opening term deposit.
7. Duration is directly proportion to opening term deposit. So customers who spend more than average duration in call should be targeted more.
8. High subscription rate are made in sep, oct,dec and mar. But no of times contacted are less. Focus more on this months will result more.
