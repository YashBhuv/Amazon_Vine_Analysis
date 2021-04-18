# Amazon_Vine_Analysis

## Analysis Overview
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

## Resources
Data Source: Amazon Review datasets, Video Games Review dataset
Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

## Results
### Total number of reviews
Vine reviews
![1](https://user-images.githubusercontent.com/64053195/115152455-293a4300-a03f-11eb-9794-3717a64e79f1.png)

Non-Vine reviews
![2](https://user-images.githubusercontent.com/64053195/115152465-32c3ab00-a03f-11eb-8eb4-1078796b6f7f.png)

### Total number of 5-star reviews
Vine reviews
![3](https://user-images.githubusercontent.com/64053195/115152476-3c4d1300-a03f-11eb-994a-e678b0e93803.png)

Non-Vine reviews
![4](https://user-images.githubusercontent.com/64053195/115152482-44a54e00-a03f-11eb-9ff8-d563cdf47490.png)


### Percentage of 5-star reviews
Vine reviews
![5](https://user-images.githubusercontent.com/64053195/115152492-4c64f280-a03f-11eb-9621-212b0922f720.png)

Non-Vine reviews
![6](https://user-images.githubusercontent.com/64053195/115152505-571f8780-a03f-11eb-916c-4b7e92ba933e.png)

## Summary
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

