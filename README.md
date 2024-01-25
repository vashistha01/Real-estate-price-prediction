# Real-estate-price-prediction
Real Estate Price Prediction is the process of estimating or forecasting the future prices of real estate properties, such as houses, apartments, or commercial buildings. The goal is to provide accurate property rates to buyers, sellers, investors, and real estate professionals to make informed decisions about real estate transactions.

Steps to follow before working:-
1.Gather relevant data from various sources, including real estate databases, government records, online listings, and other public or private sources.
2.Clean and prepare the collected data by handling missing values, removing outliers, and converting categorical variables into numerical representations.
3.Create new features or transform existing ones to capture important information that can influence real estate prices.
4.Explore and visualize the data to gain insights into its distribution, correlations, and patterns.
5.Choose appropriate machine learning algorithms or predictive models for the task.
6.Train the selected model on the training data, optimizing its parameters to make accurate predictions.

Dataset:- https://statso.io/real-estate-prediction-case-study/

1. Importing the necessary Python libraries and the dataset

   The dataset contains 7 columns. Here’s a brief overview of the columns:-
   1.Transaction date: The date of the real estate transaction.
   2.House age: Age of the house in years.
   3.Distance to the nearest MRT station: Distance to the nearest Mass Rapid Transit station in meters.
   4.Number of convenience stores: Number of convenience stores in the vicinity.
   5.Latitude: Latitude of the property location.
   6.Longitude: Longitude of the property location.
   7.House price of unit area: House price of unit area.

3. Make sure data doesn't contains any null values or missing values.
4. Check the descriptive statistics of the dataset.
5. Look at the histograms of all the numerical features.
   
   The histograms provide insights into the distribution of each variable:-
   1.House Age: This shows a relatively uniform distribution with a slight increase in the number of newer properties (lower age).
   2.Distance to the Nearest MRT Station: Most properties are located close to an MRT station, as indicated by the high frequency of 
     lower distances. There’s a long tail extending towards higher distances, suggesting some properties are quite far from MRT 
     stations.
   3.Number of Convenience Stores: Displays a wide range, with notable peaks at specific counts, like 0, 5, and 10. It suggests 
    certain common configurations in terms of convenience store availability.
   4.Latitude and Longitude: Both show relatively concentrated distributions, indicating that the properties are located in a 
     geographically limited area.
   5.House Price of Unit Area: Displays a right-skewed distribution, with a concentration of properties in the lower price range and 
     fewer properties as prices increase.
   
6.Creation of scatter plots to explore the relationships between these variables and the house price.
  
  The scatter plots revealed interesting relationships between various factors and house prices:-
  1.House Age vs. House Price: There doesn’t seem to be a strong linear relationship between house age and price. However, it appears 
    that very new and very old houses might have higher prices.
  2.Distance to the Nearest MRT Station vs. House Price: There is a clear trend showing that as the distance to the nearest MRT 
    station increases, the house price tends to decrease. It suggests a strong negative relationship between these two variables.
  3.Number of Convenience Stores vs. House Price: There seems to be a positive relationship between the number of convenience stores 
    and house prices. Houses with more convenience stores in the vicinity tend to have higher prices.
  4.Latitude vs. House Price: While not a strong linear relationship, there seems to be a pattern where certain latitudes correspond 
    to higher or lower house prices. It could be indicative of specific neighbourhoods being more desirable.

7.Performing a correlation analysis to quantify the relationships between these variables, especially how each one correlates with the house price.

   The correlation matrix provides quantified insights into how each variable is related to the others, especially with respect to the    house price:-
   1.House Age: This shows a very weak negative correlation with house price (-0.012), implying that age is not a strong predictor of 
     price in this dataset.
   2.Distance to Nearest MRT Station: Has a strong negative correlation with house price (-0.637). It indicates that properties closer 
     to MRT stations tend to have higher prices, which is a significant factor in property valuation.
  3.Number of Convenience Stores: Displays a moderate positive correlation with house price (0.281). More convenience stores in the 
    vicinity seem to positively affect property prices.
  4.Latitude and Longitude: Both show a weak correlation with house prices. Latitude has a slight positive correlation (0.081), while 
    longitude has a slight negative correlation (-0.099).

8. Building a regression model to predict the real estate prices by using the Linear Regression algorithm.
9. Visualizing the actual versus predicted values to assess how well our model is performing.


   
