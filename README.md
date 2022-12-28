# Big Data

## Technology Used

The project used multiple different technologies.  We used Google Colab as the platform and manipulated the data with PySpark.  We set up a AWS database server and set up S3 buckets to hold the data for the Postgres SQL connection.

## Analysis

### Overview:

  The purpose of this analysis is to determine if there is a difference in how people will rate objects based on if they are paid for the review or not paid for the review.  Overall this was an interesting data set with bringing the information from Amazon directly. 
  
  
### Results:

 1. The total number of vines reviews is 94 reviews and non vine reviews is 40471.
    
![image](https://user-images.githubusercontent.com/103297084/195888457-477a803d-6ff9-4fca-a13b-9cd7b6a92b3d.png) ![image](https://user-images.githubusercontent.com/103297084/195888543-0f6e937f-62d0-4a81-bbe8-31694ef0aa0f.png)

 2. The total number of 5 star views within the vine reviews is 45 and then non vine reviews is 15663.
    
![image](https://user-images.githubusercontent.com/103297084/195889130-738627df-daef-4e9b-871f-66c6a56dfeb2.png)  ![image](https://user-images.githubusercontent.com/103297084/195889205-85707000-4b32-4191-a973-cff0d2e500f6.png)

 3. The percentage of Vine reviews with a 5 star rating is 51%.  The percentage of non Vine 5 reviews with a 5 star rating is 39%.
    
![image](https://user-images.githubusercontent.com/103297084/195889695-c2177229-4289-4b83-9c6e-7cec59ed1097.png)  ![image](https://user-images.githubusercontent.com/103297084/195889760-18997d00-3fa3-4d26-9938-956a8a47fa50.png)


### Summary:

  The results of this analysis determine that there is a higher number of people who will leave a 5 star review on a product where they are paid for it.  With a higher percentage of 5-star reviews at 51%; however that is a much smaller sample size with only having 94 total reviews compared to the 40471 reviews for the non Vine reviews.  However when being paid for the review it would make sense that more 5 star reviews would happen no because of bias, but more people are actually leaving a review.  People tend to leave reviews when something is wrong and are upset with a product.  Frequently people will not leave reviews if they are happy with the product.  Human tendencies need to be taken into account when analyzing this data.  Overall I would look change the data sets for future analysis to include 4 and 5 star reviews in order to take in the human tendencies when giving a review.
