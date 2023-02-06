### Difference between food delivery (Glovo) and eating out (TripAdvisor)
![image](https://user-images.githubusercontent.com/121023453/216969510-caddf3c4-d1f0-4afd-978f-846fb01d9587.png)
We want to find out more about the differences which types of food are popular, the rating and *****

We found a TripAdvisor dataset on Kaggle with data of 125000 restaurants in Europe (https://www.kaggle.com/datasets/damienbeneschi/krakow-ta-restaurans-data-raw), first we cleaned the data by removing restaurants in all cities other than Barcelona, removing columns we don't need and we ended up with a dataframe of 8425 restaurants in Barcelona with name, cuisine style, the rating and amount of reviews. 

To get similar data from Glovo, we used data scraping. By using data scraping we got the restaurant name, cuisine style, rating and amount of reviews from 1516 restaurants in Barcelona.

When merging those columns by name we only had about 110 exact matches, then I went back to the dataset and figured that the dataset was uploaded over 5 years ago. For that reason we decided to also use webscraping for TripAdvisor instead of using this dataset. By doing that we got the same information from 9700 restaurants in Barcelona.



