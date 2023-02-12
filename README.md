
# AIR BNB BOOKIN ANALYSIS

Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.
This dataset has around 49,000 observations in it with 16 columns and it is a mix between categorical and numeric values.

# What is AIRBNB?
Airbnb, Inc., based in San Francisco, California, operates an online marketplace focused on short-term homestays and experiences. The company acts as a broker and charges a commission from each booking. The company was founded in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia.
## DataSet
[Dataset](https://drive.google.com/file/d/1zylXAoVfDJpVH7QSSmQ4swJI7yav-U-l/view?usp=share_link)

## Approach Architecture
![image](https://user-images.githubusercontent.com/33152425/218307787-385dc242-f55f-4163-a3ff-a70d8a474790.png)


## About the data
- 48895 Row, 16 - Column
- Categorical data : host name, neighbourhood_group, neighbourhood, room_type
- Data Has int, float and object data type
- Id : It is unique for each bookings, numeric values, data is not repeatable .
- name : How is the room. Ex : Clean & quiet apt home by the park, this can be neglected.
- host_id : ID of the host, Data is repeatable, Numerical data .
- host_name : Name of the host. This column is neglected, Categorical data .
- neighbourhood_group : It is borough (a town that has its own goverment ). Brooklyn,Manhattan, Queens, Bronx, Staten Island .
- Neighbourhood: Place of the location  inside neighborhood group.
- Latitude : Numerical values , Position of the location.
- Longitude :Numerical values , Position of the location.
- room_type : Private, Shared or Entire/Home, Categorical value.
- price : Cost of the room, Numerical value.
- minimum_nights : How many days compulsory to stay.
- number_of_reviews : Total number of review for this host
- last_review :  Give information regarding  last reviews is given in date.
- reviews_per_month : Total number of reviews / Days in months
- calculated_host_listings_count : The total number of apartments and bedrooms referred to the same landlord.
- availability_365 : Days it is available in a year

## Tools used
- Google Colab is used as IDE.
- Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
- For visualization of the plots, Matplotlib and Seaborn are used

![image](https://user-images.githubusercontent.com/33152425/218307513-8992348e-1f0c-4afa-bba1-fc7ab292f114.png)

## Some plots of Data Analysis
![image](https://user-images.githubusercontent.com/33152425/218307608-754ff0d3-d157-4aa8-ae57-542a6872d8d7.png)
![image](https://user-images.githubusercontent.com/33152425/218307616-753bcc8a-ee3e-4fac-a232-f2bc37ff36f2.png)
![image](https://user-images.githubusercontent.com/33152425/218307620-2fc7de46-a7ec-45d0-871d-ceccab35498c.png)
![image](https://user-images.githubusercontent.com/33152425/218307627-83aedf69-0841-4414-bf43-8e6036ef917b.png)
![image](https://user-images.githubusercontent.com/33152425/218307634-23d8a062-c2c1-43d7-a05d-b051c6951736.png)
![image](https://user-images.githubusercontent.com/33152425/218307637-17fa00ac-c919-4f65-9b86-a2d7be9d52e4.png)
![image](https://user-images.githubusercontent.com/33152425/218307642-a7ad2b11-babd-432a-bc2f-cf978e3169ba.png)
![image](https://user-images.githubusercontent.com/33152425/218307649-31e656f8-43b2-491f-9620-303536a6a8a1.png)
![image](https://user-images.githubusercontent.com/33152425/218307652-003868d3-d523-473c-9ea2-50670b3c6bbf.png)
![image](https://user-images.githubusercontent.com/33152425/218307658-df4fade0-80f3-477c-8c23-c3025cb0ecf3.png)

## Conclusion
- In this analysis project, about 14 different cases were analyzed on the given dataset to make better business decisions and help analyze trends, which can lead to new and better products and services. It has been found that Most of the Bookings were takes place for the "Manhaton" of around “44.3%" followed by “Brooklyn", “Queens" which has “41.1%" & "11.6%" respectively. 
- We have also analyzed that, Manhattan has the highest range price for the listings with about dollar 140 as an average price, followed by Brooklyn with $90 per night, Queens and Staten Island seem to have a very similar distribution, The Bronx is the cheapest.
- Additionally, we also find-out the Top (Host). Preference of Guests w.r.t. Property Type & Room Type. Furthermore, we have also been analyzed Customer Reviews/Comments,  provided by the Airbnb’s and many more.

## Acknowledgements

 - [Kaggel](https://www.kaggle.com/code/subhradeep88/airbnb-analysis-eda/notebook)
 - [Towards Data Science](https://towardsdatascience.com/data-cleaning-and-eda-on-airbnb-dataset-with-python-pandas-and-seaborn-7c276116b650)
 - [Analytics Vidya](https://www.analyticsvidhya.com/blog/2021/10/end-to-end-predictive-analysis-on-airbnb-listings-data/)


## Demo



https://drive.google.com/file/d/1wdGtc_uH5nvCfjSbj5NtpWo6exnZrSKr/view?usp=share_link
## Documentation

[Documentation](https://colab.research.google.com/drive/1L_l_9b0rHkQUX1ZQt-KpyS47XBbS5GaY?usp=share_link)

