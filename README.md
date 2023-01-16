# House_Price_Prediction :houses::house_with_garden::dollar:
 
## Overview of the Project :scroll:

The housing market is subject to the same economic laws of supply and demand as every other industry. When there are more buyers than sellers, the supply of houses goes down, and demand increases, making houses harder to buy and more expensive. In addition to the supply and demand of a market, the characteristics of units being sold also affect the selling prices of homes. A property's size, location, appearance, and other features can affect its demand and price. The state of the economy, interest rates, real income, and changes in the size of the population also influences the housing market. Over time, the price of houses fluctuates. If you want to buy a home, understanding what makes prices go up helps you know when and where you'll get the best price for a home. We aim to make our evaluations based on every basic parameter that is considered while determining the price of a housing unit. Using a machine learning model, we will make predictions to try to achieve a high accuracy score.

## Link to Presentation

Click the [link](https://docs.google.com/presentation/d/1uETFlwjuOJqFBKV2HDUrnMW87aWxBhDpTHLkDI9pQpk/edit#slide=id.gc6f9e470d_0_0) to see the project presentation in Google Slides.

## Link to Dashboard 

We created a dashboard using HTML and CSS to display project overview and visualization via Tableau from data collected in PostgreSQL

The Viz of the dataset can be viewed [here.](https://public.tableau.com/app/profile/neeraja.v6475/viz/TableauHousePricesDistribution/Dashboard1?publish=yes)

## Communication Protocols :phone:

For effective peer-to-peer communication, slack was used for team channel creation/messaging and zoom for team meetings.

## Technologies and Tools Used

* ![](https://img.shields.io/badge/Python-yellow?style=for-the-badge)
* ![](https://img.shields.io/badge/Jupyter_Notebook-orange?style=for-the-badge)
* ![](https://img.shields.io/badge/Excel-green?style=for-the-badge)
* ![](https://img.shields.io/badge/Visual_Studio_Code-blue?style=for-the-badge)
* ![](https://img.shields.io/badge/PgAdmin-lightgrey?style=for-the-badge)

## Database

* ![](https://img.shields.io/badge/PostgreSQL-blue?style=for-the-badge)

PostgreSQL is used for data storage, processing, retrieval, and analysis to support finding insights from our Houston Houses Merged Data.

A mockup of the code to write the house data to the postgres data base can be found here: **[link](./03_Code_and_Data/04_Database/04_Database_houseData.ipynb)**.

Similarly, the crime statistics table is saved to the data base using the following code: **[link](./03_Code_and_Data/04_Database/04b_Save_to_Database_crimeData.ipynb)**.

## Resources/Data Sources

Data for analysis has been extracted from [RapidAPI.com](https://rapidapi.com/apimaker/api/zillow-com1)

#### Zillow.com API Documentation (apimaker) | RapidAPI

Unofficial API. US and CA real-time real estate data. Search by coordinates and MLS. Get similar properties for sale or sold property, Zestimate (rent estimate) and other data from Zillow. This site allows us to explore and extract data from two APIs endpoints:
* Property details
* Property Extended Search

Additionally, crime statistics per zip code for the city of Houston was obtained from the Houston police department website. 

The code used to gather the house data is here: **[link](./03_Code_and_Data/01_Gathering/01a_Get_House_Data.ipynb.ipynb)**.
The code used to gather the crime statistics data is here: **[link](./03_Code_and_Data/01_Gathering/01b_Get_Crime_Data.ipynb)**.

The data was merged using this code: **[link](./03_Code_and_Data/02_Merging/02_Merge_Data.ipynb)**

## Questions We Would Like to Answer :memo:

* Does year-built affect property value?
* What home feature decreases the property value?
* What home feature raises property value the most?
* School quality/ranking have an impact in property value?

## Data Preprocessing

Pandas library is used to perform the data manipulation in Python. Pandas library is extremely powerful and helped us to simplify data cleaning tasks like data inspection, data fill, loading and saving data, mergers and join, duplicate, import data and much more.

A folder containing three files with code to pre-process the data can be found here: **[link](./03_Preprocessing/)**


## Implementing machine learning model(s)

For this analysis, we used three different machine learning models, which are Linear Regression, Random Forest, and XGBRegressor. In comparing the three models, the XGB Regressor model was far more accurate. The model had a 0.75% accuracy in predicting the house prices in the Houston, Texas, area. The top four features of importance are constructed area, lot area sqft, zip code, and year built.

Machine learning is an iterative process. This first round of data exploration and model evaluation was an excellent start to gain insights quickly and get a reasonably good model prototype. This dataset has much structure, and further work is required to build a high-performing prediction model.

The machine learning model code mockup can be found here: **[link](./ML_House_Prediction_Prices_Updated.ipynb)**

![image](https://user-images.githubusercontent.com/110510718/210690711-f92b45c7-96d5-4d60-8efe-1cee33e03f05.png)


## Results of Analysis

## Project Summary
