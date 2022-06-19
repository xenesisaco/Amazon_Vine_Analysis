# Overview
The Amazon Vine program allows its users to write reviews of its manufacturers and providers and we must determine if the reviews were written by these members. 


# Purpose
Using a new database with Amazon RDS and connecting it to the AW server, the database was queried  and tables were produce with products, customers, review IDs and ultmatlely the reviews. 

Then utilizing the table and connecting it to pgAdmin, we were able to populate the date. 

# Results

1. 403,807 Amazon for books with "helpful" votes. 
2. 403,807 reviews with 242,889 were 5 stars
3. all 5 star came from the vine program. 

![3](https://user-images.githubusercontent.com/98041751/174498000-ab40a067-8340-4fd5-800e-53beac9d3b01.png)

![1](https://user-images.githubusercontent.com/98041751/174498001-6eb0823d-fcde-4724-b0bc-47b139eac92c.png)

![2](https://user-images.githubusercontent.com/98041751/174498002-1b2ac55f-1ace-4632-99b9-ca3bab29eab7.png)



# Summary

With the Vine program not having any 5-star reviews, this couold become suspicious and non-organic, creating mistrust. 
We can pinpoint certaain keywords or phrases useing a jargon analysis and compare non-vine rewviws to see if there are vast cobtrasts or differences. 
