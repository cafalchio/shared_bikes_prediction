# Shared bikes: A prediction based on wheater data

It is an intersting dataset in which wheater data was recorded together with the use of shared bikes. The XGboost regression model got 95% r2 score.

Libraries
---------

 * numpy,
 * pandas,
 * matplotlib,
 * sklearn,
 * scipy,
 * tqdm,
 * seaborn,
 * datetime,
 * math,
 * warnings
  
Motivation 
---------
  My major motivation was my personal use of shared bikes. As a user, I did not understand why sometimes all the bikes are gone at the station close to my home. The project here give a better idea of when the bikes are used.

Files
---------
  blog_regression.ipynb - jupyter notebook containing the analysis
  
  hour.csv - csv file containing the data sampled hourly
  
  bikes_day.csv - csv file containing the data sampled daily
  
Summary
---------
1. Data exploration and explotatory analysis
2. Showing that temperature affects bike renting daily and working day the hourly data
3. Two models that predicted the amount of bikes daily and hourly with great precision
