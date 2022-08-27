# Amazon_Vine_Analysis
## Overview of Analysis
This analysis' goal was to analyze the Amazon Vine program to determine if there is any bias towards more positive reviews from Vine members. This analysis was preformed using AWS and its RDS service, transforming data into pgAdmin and preforming an ETL with the help of PySpark and google colab. 
## Why this dataset was chosen 
The chosen dataset was for Video Games, it was chosen due to the analysts long history and experience with video games and their interest in them. This dataset immediately jumped out as a clear winner for an interesting analysis.
## Resources and Software used
- AWS, Google Colab Notebooks, pgAdmin, PostgresSQL
- Data was sourced from https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt
## Results of the Analysis
### Total Reviews
- Paid reviews
![mod16_paid_reviews](https://user-images.githubusercontent.com/102084269/187047848-d291ab75-4e0d-4429-9061-faedbcd17ce3.PNG)
- Unpaid reviews
![mod16_unpaid_reviews](https://user-images.githubusercontent.com/102084269/187047869-2d1f52e1-4847-4403-8d07-5d747d3bca11.PNG)
### Total of 5 Star Reviews
- Paid reviews
![mod16_paid_five_star](https://user-images.githubusercontent.com/102084269/187047897-387ce336-57c4-4f5c-a611-4bc1002c7bad.PNG)
- Unpaid reviews
![mod16_unpaid_fivestar](https://user-images.githubusercontent.com/102084269/187047902-75b2123d-27ea-4bdf-9080-f734ca1e825f.PNG)
### Percentage of the Five Star reviews
- Paid reviews
![mod16_five_star_percent](https://user-images.githubusercontent.com/102084269/187047914-cdc58391-7435-4402-9b80-bbcdd784ba70.PNG)
- Unpaid Reviews
![mod16_five_star_unpaid_percent](https://user-images.githubusercontent.com/102084269/187047923-efe2e00e-4e4e-4b04-a298-dd2a2c65fb4d.PNG)
