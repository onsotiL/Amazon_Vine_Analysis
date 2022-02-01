# Amazon_Vine_Analysis
The purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. PySpark was used to perform the ETL process  by extracting the dataset, transform the data and connect to an AWS RDS instance, and load the transformed data into pgAdmin

## Results: 
Total paid Vine reviews 
![image](https://user-images.githubusercontent.com/90416094/152027890-a0b47d42-0e2d-4a82-8a2a-69cd64cb1027.png)

Total unpaid Vine reviews 
![image](https://user-images.githubusercontent.com/90416094/152027913-e3772f2d-3762-483e-ae03-88c587f193df.png)

Total paid 5-star Vine reviews 
![image](https://user-images.githubusercontent.com/90416094/152027974-16814fec-7b64-40a8-87ab-21189337f200.png)


Total unpaid 5 stars Vine reviews 
![image](https://user-images.githubusercontent.com/90416094/152028015-bdb11326-e290-4a0a-9aaf-3f8d55e370fe.png)

Percentage of Vine reviews that were paid 
![image](https://user-images.githubusercontent.com/90416094/152027792-ac3cbc6b-d3d7-419b-a016-9da6f9c56726.png)

percentage of non-Vine reviews were 5 stars
![image](https://user-images.githubusercontent.com/90416094/152027857-da59c3c0-1467-4710-a7e4-9cc89e865e0c.png)

## Sumarry 
According to the analysis of the dataset, more than half of the reviews in the program were star at 51%. The percentage of the unpaid non vine reviews were lower at 39%. This demonstrates a positive bias towards the reviews in the vine review program 

An additional analysis is recommended to support the statement
