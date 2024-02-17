# bank-customer-churn-dashboard
It is the Bank customer churn dashboard built using Power BI. I have analysed data across various categories such as satisfaction rate, complain rate, according to gender, age and a lot more.
I used DAX formulas to create measures and columns to analyse and visualize the data in detailed and comprehensive manner.
It includes multiple reports according to different analysis and visualization criteria such as different reports for "Gender Based Analysis" and another different report for "Age Based Analysis".

**Check the screen recording of the dashboard from here** :- https://www.linkedin.com/feed/update/urn:li:activity:7164312659830530049/

Different Analysis done according to different reports are given below :-

**1) Main Report Page :-**

![main report page of customer churn dashboard](https://github.com/ujjwal717/bank-customer-churn-dashboard/assets/93403224/020aac0b-65e1-4936-89fe-1e401d2425b9)


Various Slicers :- 

A) Customer Exited ?
B) Customer has Credit Card ?
C) Select Country 

Bookmark Navigators :- 

A) Analysis by Gender
B) Analysis by Age 

Various Analysis - Visuals :- 

A) **Average Salary** - Guage
B) **Average Age** - Guage
C) **Customers by Credit Score** - Treemap
D) **Customers by Complain** - Column Chart
E) **Customer by Satisfaction Score** - Pie Chart
F) **Inactive Customers** - Card
G) **Active Customers** - Card
H) **Total Customers** - Card


**2) Analysis by Gender :-**

![analysis by gender 2](https://github.com/ujjwal717/bank-customer-churn-dashboard/assets/93403224/00c3728f-d2c3-4bef-b693-e4ad45241d91)




Various Slicers :- 

A) Customer Exited ?
B) Customer has Credit Card ?
C) Select Country 

Various Analysis - Visuals :- 

A) **Customers by Card Type and Gender** - Side by Side column chart
B) **Customers by Purchased Products and Gender** - Line Chart
C) **Customers by Tenure in Bank and Gender** - Stacker bar chart
D) **Average Female Salary** - Guage
E) **Average Male Salary** - Guage
F) **Female Customer Count** - Card
G) **Male Customer Count** - Card


**3) Analysis by Age :-**


![analysis by age](https://github.com/ujjwal717/bank-customer-churn-dashboard/assets/93403224/a7856435-d5ce-4216-b098-2c03e525adfc)



Various Slicers :- 

A) Customer Exited ?
B) Customer has Credit Card ?
C) Select Country 


Various Analysis - Visuals :- 

A) **Customers by Complain and Age Interval** - Stacked Bar Chart
B) **Customers by Age** - Line and Stacked Column Chart
C) **Average Balance of Customers by Age Interval and Gender** - Line Chart
D) **Customer by Points Earned and Age Interval** - Ribbon Chart


**Below are the images and various insight that we found from the analysis and the possibel reason for it**

**1) Insight from the Main Report of the Dashboard :-**

![Customer Exited from main report page](https://github.com/ujjwal717/bank-customer-churn-dashboard/assets/93403224/b06ea9cc-ca81-49d3-8250-80327364fff1)


**A) Customers by Complain :-** Complains are the requests/reports/problems that customers files in the bank for any inconvenience

Insight :- We can see that out of 2038 customers that exited the bank, 2034 customers had complains.

Possible Reasons :- They might have exited the bank because their problem would not have been addressed properly.



**B) Customer by Satisfaction Score :-** Satisfaction Score is the score provided by the customers after solution of hus/her problems.

Insight :- It can be seen that around 40% of the customers that exited gave bad (less than 3 out of 5) satisfaction score.

Possible Reason :- They might not have been satisfied from the resolution that they got or the customer executive could have been rude.


**C) Customers by Credit Score :-**

Insight :- Maximum customers that exited the bank were having bad credit score. Many of them also hasd good credit score and least were having excellent credit score.

Possible Reason :- The reason that customers having bad credit score exited the bank might be from the fact that they might have applied for any kind of load and got rejected because of bad credit score. 


Some more analysis in brief :- 

1) Average Salary of exited customers is 101.5k USD.
2) Average Age of exited customers is 44.8
3) Out of 2038 exited customers, 1303 were Inactive
4) Out of 2038 exited customers, 735 were Active




**2) Insight from Gender Report of the Dashboard :-**

![Customer exited by gender](https://github.com/ujjwal717/bank-customer-churn-dashboard/assets/93403224/33b34a56-5d7b-4c75-b7a1-ae45f01a0486)


**A) Customers by Card Type and Gender :-**

Insight :- It can be seen that out of exited customers, for each and every card type, female customers have exited the bank more than the male customers. On the contrary if we select **"No"** in the customer exited slicer, we can see that male customers are more for having all the different kind of cards so, male customers exit less than female customers for every card type.

Possible Reason :- We wre getting this insight as overall, female customers left more than male customers. Other than that, if we focus on specifc card type, diamond card holders are the ones who exited the most for both the genders.

**B) Customers by Product Purchased and Gender :-**

Insight :- It can be seen that most of the customers that exited were having One product purchased from the bank. Here Product is same as services such as home loan, car loan, credit card, insurance, FD, RD and more.

Possible Reason :- The reason for this can be, it's easier for customers to change bank if he/she has less number of products purchased as it's easier to settle the outstanding amount and other required documentation, while customers having large number of products purchased from the bank need to do a lot of documentation and settlement before closing their account which is tedious for customers.

**C) Customer by Tenure in Bank and Gender :-**

Insight :- Here, It can be seen that really old customers (in terms of their bank account tenure) are leaving the bank which is not a good sign at all as losing trusted and old customers is not good for any company at all. Also, for all the tenure intervals, female leave the bank more than male customers.

Possible Reason :- The possible reason for it can be that the customers might be having some serious problem from the bank as customer who has account in a bank for around 7-10 years will not leave/exit the bank for a really small problem.

Some more analysis in brief :- 

1) Count of Exited Female Customers is 1139
2) Count of Exited Male Customers is 899
3) Average Salary of Female Customers is 102.95k USD
4) Average Salary of Male Customers is 99.96k USD










