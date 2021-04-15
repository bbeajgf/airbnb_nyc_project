# airbnb_nyc_project
Airbnb in NYC Data Analytics Project

Airbnb is one of lodging company service concerning in homestay rentals for vacation or tourism activity established in 2008 and based in San Fransisco, California. Airbnb does not own any of the property; instead, it profits by receiving commission from each booking. Airbnb can be accessed easily either in thw website or the official mobile apps. We can find the best listing based on our preferences everywhere we will visit and sort it as our budget and accomodation preferences.
![Airbnb-NYC-law](https://user-images.githubusercontent.com/76248569/114740486-16d8b480-9d74-11eb-8d1c-8aa6919c98a0.jpg)


In this analysis, I am going to do basic analysis based on the dataset of Airbnb NYC I got from Kaggle.com (dataset source: https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data). This whole dataset describes all of listing and metrics in NYC, NY for 2019. It contains 16 columns and 48895 rows. The goal of Airbnb NYC Data Analytics is to get more insights as much as we want from the raw dataset!

For the listing code can be seen in the attached ipynb file.

Here are some insights I get:

1. New York City has 5 region areas as known as Five Boroughs. There are Manhattan, Brooklyn, Queens, Bronx, Staten Island. The proportion percentage number of listing in each region can be shown in this figure below. 
![airbnb nyc area](https://user-images.githubusercontent.com/76248569/114749133-cd409780-9d7c-11eb-9e37-d66d89ac1fe1.png)
From the pie chart above, we can see the whole listing location mostly located in Manhattan and Brooklyn with 44.3% for Manhattan and 41.1% for Brooklyn. 

2. Let's get into the smallest area! From the 5 region areas or Boroughs, it is separated into hundreds of district neighbourhood. In this plot, I do analysis by counting top 20 cities to make it more specifically and we get the top 20 listing city locations
![sub area](https://user-images.githubusercontent.com/76248569/114749247-efd2b080-9d7c-11eb-8737-1f795def7a55.png)

3. After we get the summary of listing location, let's look into the listing type. Based on the analysis, we see that the listing host is available in 3 different room type: Entire home/apartment, Private Room, and Shared Room
![room type](https://user-images.githubusercontent.com/76248569/114749283-fa8d4580-9d7c-11eb-852d-1a066ff5d445.png)
From the chart above, half of listing room type number is in Entire Home/Apartment and another choice is Private Room. There is less than 3% of shared room.

4. Next analysis is the top host. It is possible for a host (the one who rents their property) has more than one property rented. So we got the top 10 of it.

![top-host](https://user-images.githubusercontent.com/76248569/114749329-07aa3480-9d7d-11eb-9013-a253881bdebc.png)

5. Next, we want to know about the distribution of listing type in each region. After do some analysis, we can see the number of available room for each region.

![roomvsarea](https://user-images.githubusercontent.com/76248569/114749623-53f57480-9d7d-11eb-8c2f-503d40768be9.png)

From the chart above, we can conclude Private Room listing dominates in Brooklyn, Queens, and Bronx. If the guest's destination is Manhattan, the number of entire home/apartment is high (but they can choose private room)

6. The another important aspect of choosing the best listing is Price. The chart below shows the average listing price for each region in USD $ and Manhattan' average price for the listing is the highest than other and the lowest average price is Bronx
![average price of area](https://user-images.githubusercontent.com/76248569/114749678-61126380-9d7d-11eb-96b3-251cccc0f185.png)

7. Let's deep-dive a little bit. If the previous point is the average of the whole listing, this chart shows the average of each room for each region
![avg room price by area](https://user-images.githubusercontent.com/76248569/114749738-712a4300-9d7d-11eb-988f-142b840f13f4.png)

8. To get more insight about the listing location distribution in each Boroughs in a map scatter plot below
![neighbourhood](https://user-images.githubusercontent.com/76248569/114749824-8a32f400-9d7d-11eb-9870-a23b13f9d364.png)

9. The last analysis. The distribution of listing's price can be seen in a map scatter below. We can assume if 20% of all listing price are above the average price especially in Manhattan area
![price distribution](https://user-images.githubusercontent.com/76248569/114749866-95861f80-9d7d-11eb-9c2d-152449214965.png)

10. The last, the chart below describes the distribution of room type in the top 15 neighbourhood or the city
![roomvssubarea](https://user-images.githubusercontent.com/76248569/114749899-9f0f8780-9d7d-11eb-8890-7628bea147ea.png)

That is all the conclusion of NYC's Airbnb Data Analysis and Visualization. Still need more to improve and feel free for the feedback! Thank you for reading!
