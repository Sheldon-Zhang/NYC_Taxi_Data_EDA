# NYC_Taxi_Data_EDA

Objective:  
Imagine that you decide to drive a taxi for 10 hours each week to earn a little extra money. Explain how you would approach maximizing your income as a taxi driver.
If you could enrich the dataset, what would you add?  Is there anything in the dataset that you don’t find especially useful?


Data:  
Yellow taxi data dictionary 
taxi zone lookup table

Notes:  
Yellow Medallion Taxicabs - These are the famous NYC yellow taxis that provide transportation exclusively through street-hails. The number of taxicabs is limited by a finite number of medallions issued by the TLC. You access this mode of transportation by standing in the street and hailing an available taxi with your hand. The pickups are not pre-arranged.

Solution assumptions:
1. As a taxi driver, I have pretty flexible hours as to when to drive.
2. I am driving a sedan, which means I could carry no more than 4 passengers at the same time.

In order to maximize income, two questions need to be answered:  
Q1. What is the best working schedule per week?  
Q2. During the my working hour, where should I head next after finishing each ride?

To answer the first question:  
I simply create a simple plot that count the everage daily.

