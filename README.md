# Webscraping
Webscraping the used car platform 12gebrauchtwagen.de to perform a non - linear regression on the prices.

Our group project consist of three parts:
1. A modular webscraper which in theory is able to scrape 120 pages * 20 listings of each brand and save the retrieved data in a csv file (a sample for one brand is provided)
2. Data cleaning in order to get a better overview and be able to perform data analysis 
3. We fit a non linear regression model were the price is the dependent variable and mileage and power represent the two independent variables (price is predicted based on milage and power). Then we plot all listings 
in a 3D scatterplot with the non-linear regression and save the listings which the model suggests are underpriced through a predefined threshold. 

Limitations:
Only mileage and power are used to explain the price (registration date, model, fuel type etc.) are also relevant factors influencing the price.
