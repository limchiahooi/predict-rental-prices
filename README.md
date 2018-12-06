# Predict Rental Prices
This repo contains the Predict Rental Prices project as part of my data science portfolio. The rental prices were scrapped from a property website based on properties located in Malaysia. Three different types of algorithms were used to train the models which consist of two machine learning (ML) and one deep learning (DL) algorithm. This project focuses on comparing the performance and results of these three algorithms instead of explaining the theory behind the algorithms as it assumes that readers already familiar with these algorithms. For readers who are in a hurry, they can dive straight into section 4. Discussion and Conclusion.

1. Linear Regression
2. Random Forest
3. Tensorflow with Keras
4. Discussion and Conclusion

## Dataset
The rental prices were scrapped from a property website based on properties located in several states in Malaysia i.e. Kuala Lumpur, Selangor, Putrajaya and Johor. The data has been intentionally messed up and contain duplicates and errors in order to demonstrate the data wrangling / munging steps required to clean the data before using it to train the models. To know how to scrap web data using Python, kindly refer to my other project on [Web Scraping Project](https://github.com/limchiahooi/web-scraping-rental). 

**Why predict rental prices?** 
Firstly, it is an extension of my web scraping project. After the data has been scrapped, it is a natural progression to explore and model the relationships between the property features and the rental prices. Secondly, many research / tutorials have been focusing on training models to predict property selling prices, but relatively few on predicting property rental prices. This project aims to fill the gap and provide useful insights to property investors to help in their decision-making as to which property to purchase and rent out in order to maximize rental yield.