# Amazon Vine Analysis
## Overview
The purpose of this project is to determine if there is any bias toward facorable reviews from VIne members in my data set using different programs such as using PySpark to perform ETL on the dataset, connecting to an AWS RDS instance, and loading the data into PgAdmin to review the data. Using PySpark, Pandas, and SQL to determine if there are any bias. 

## Results
- Q: How many Vine reviews and non-Vine reviews were there?
  - A: There are a total of **1207** vine review, and **97839** non-Vine reviews. 
  
  <img width="443" alt="image" src="https://user-images.githubusercontent.com/104419959/208316362-e2e5f23a-7b68-4ebd-b9a3-5ff959fd60e9.png">

- Q: How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - A: There are a total of **509** 5 stars review for Vine-paid, and **45858** for non-Vine.
  
  <img width="678" alt="image" src="https://user-images.githubusercontent.com/104419959/208316403-35a142ae-08e4-49fe-9444-6ae56f0e8c25.png">
  
- Q: What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - A: About **42.2%** are vine 5 stars review, and **46.9** are non-vine 5 star reviews. 
  
  <img width="623" alt="image" src="https://user-images.githubusercontent.com/104419959/208316440-c8bc7cee-a970-4286-856a-436fa0c25bb5.png">

## Summary
From comparing the data set for both paid and non paid Vine users, there are apparently more reviews provided by the non-vine paid users, and we can declare that there are no bias towards vine paid users, as star reviews and percentage for both categories are similiar. <br>
Another test I would do to support my conclusion is analyze the data set using mean, mode, median, and standard deviation to visualize the spread of the result. This can identify if there are any outliers among the result. 
