# airbnb-madrid
Data exploration of Madrid Airbnb dataset with r

Dataset used: http://insideairbnb.com/get-the-data.html

## Assignment on AirBnB dataset for Madrid

We decided to use the Madrid Airbnb dataset which consists of listings, details about listings, prices, reviews, ratings amongst others. Airbnb started as a small tech start-up where private people could list spare rooms and/or homes for rent to earn some extra money. As it's popularity grew, this business model changed and Airbnb are now facing scrutiny in many cities due to a lot of apartments being purchased for the sole purpose of being rented at Airbnb, driving up housing prices. We want to look at this dataset and see the level of density of Airbnb listings in different areas of Madrid, the price levels, how apartments are being rated depending on how many apartment the host owns etc. 

The questions we are asking ourselves before modeling and visualising our results are:

1. does price depend on room type and/or location?
2. are you more likely to be a super_host if you have a lower price? 
3. does the amount of houses a host has listed impact reviews and price?
4. what is the relationship between deposit and cleaning fees with reviews per month as a measure of demand?

We will also run a linear regression model to anayse which variables predict price, and a logistic model to see which variables determines if a host is a super host.

The above can be evaluated using the following variables (list not exhaustive):
1. price 
2. room_type
3. neighbourhood 
4. host_listings_count 
5. reviews_per_month
6. reviews_score_rating
