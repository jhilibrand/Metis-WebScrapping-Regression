# Web Scrapping and Regression Project

Question: 
Can we use some basic zillow features and geolocation data to predict where a home will trade? Is a listing overpriced? Is a listing stale?  

Data Description: 
My primary data set will be Zillow search results. As opposed to clicking into each listing, I will be scrapping from a results page (which will give me fewer features, but more data points). I aim to overlay outside data sources as well. I will use "sold homes" as my training set. Given data cleaning substantially cuts down the provided data, I will aim to widen my geographical area to create a more robust analysis. 

Tools/MVP: 
I will be using Beautiful Soup and Selenium for my webscraping pipeline. I will be doing the majority of my analysis in pandas, and will utlize seaborn and Scikit-learn for analysis. An MVP for this project would be a basic regression that can utilize house features and house location to predict home price. 
