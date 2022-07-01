# Amazon_Vine_Analysis

PLEASE NOTE MY CODE FOR DELIVERABLE 2 IS IN THE SAME FILE AS DELIVERABLE 1.

## Purpose and Scope

The purpose of this analysis was to look at a category of Amazon retail, and determine top products based on different metrics with an emphasis on consumer reviews.

## Results

### Vine versus non-Vine

Looking at the total row count of our filtered data of being vine sponsored versus not vine sponsored, we can see that there are 616 rows, or 616 reviews that were sponsored, as demonstrated below:

<img width="926" alt="Screen Shot 2022-07-01 at 1 15 03 PM" src="https://user-images.githubusercontent.com/99772755/176940745-45401300-53e9-4f56-bc9a-3a4f72243bc3.png">


On the other end of this, we have significantly more reviews that were sponsored, 69,432 to be exact:

<img width="1008" alt="Screen Shot 2022-07-01 at 1 19 01 PM" src="https://user-images.githubusercontent.com/99772755/176941110-bbfa1f62-d390-401d-a5ce-6bc61ef57bc2.png">


### 5-Stars

Of the 616 sponsored reviews, only 221 were 5-star reviews (35.87%):

<img width="886" alt="Screen Shot 2022-07-01 at 1 19 45 PM" src="https://user-images.githubusercontent.com/99772755/176941292-0db3d0da-fee8-4266-9eb3-0b2b3486b4c0.png">

Of the 69,432 reviews that were not sponsored, 40,525 were 5-star reviews(58.36%):

<img width="924" alt="Screen Shot 2022-07-01 at 1 19 50 PM" src="https://user-images.githubusercontent.com/99772755/176941659-2ce365f5-fcd4-4a4f-a778-62d8e4243376.png">

## Key Findings

After analyzing the different between sponsored 5-star reviews, and non 5-star sponsored reviews it does not look like there is a posititvity bias for reviews. An additional analysis that should be done is filtering out non-verified reviews to ensure that the scores given are genuine. We can then look for a bias to see if there are less verified vine reviews, which would indicate that the sponsorship decreases reliability of reviews by encouraging individuals to review products they themselves have never used. 
