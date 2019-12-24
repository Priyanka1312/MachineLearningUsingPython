# Machine Learning Using Python
![mlflow.png](images/mlflow.png)

Machine Learning is a latest buzzword floating around. It desrves to, as it is one of the most interesting subfield of Computer Science.

 __What does Machine Learning really means?__
Machine Learning is an application of artificial intelligence(AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed.

__Machine Learning focuses on the development of computer programs that can access data and use it to learn for themsleves.__
The process of learning begins with data, such as, direct experience, or instruction, in order to look for patterns in data and make better decisions in the future based on the examples that we provide. 
__The primary aim is to allow the computers learn automatically without human intervention or assistance and adjust actions accordingly__ 

__Regression in a nutshell__

Put simply, regression is a machine learning tool that helps you make predictions by learning – from the existing statistical data – the relationships between your target parameter and a set of other parameters. According to this definition, a house’s price depends on parameters such as the number of bedrooms, living area, location, etc. If we apply artificial learning to these parameters we can calculate house valuations in a given geographical area.

The idea of regression is pretty simple: given enough data, you can observe the relationship between your target parameter (the output) and other parameters (the input), and then apply this relationship function to real observed data.

__House price prediction__
To show you how regression algorithm works we’ll take into account only one parameter – a home’s living area – to predict price. It’s logical to suppose that there is a linear relationship between area and price. And as we remember from high school, a linear relationship is represented by a linear equation:

__y = k0 + k1*x__

In our case, y equals price and x equals area. Predicting the price of a home is as simple as solving the equation (where k0 and k1 are constant coefficients):

__price = k0 + k1 * area__

We can calculate these coefficients (k0 and k1) using regression. Let’s assume we have 1000 known house prices in a given area. Using a learning technique, we can find a set of coefficient values. Once found, we can plug in different area values to predict the resulting price.


# Repository Overview
This repository contains the details on the Machine Learning Analysis conducted on various datasets.

# Table of Contents

__1. Predicting Maximum Temperature using Linear Regression__

We will explore the basic use of Pandas and will cover the basic commands of Exploratory Data Analysis(EDA) which includes cleaning, munging, combining, reshaping, slicing, dicing, and transforming data for analysis purpose. We will also develop a regression model to predict the Maximum Temperature.

Based on the weather data in the Summary of Weather dataset, develop a predictive model to determine the Maximum Temperature on a given day.

The dataset contains information on weather conditions recorded on each day at various weather stations around the world. Information includes precipitation, snowfall, temperatures, wind speed and whether the day included thunder storms or other poor weather conditions.

__2. Car Sales Prediction(Forecasting Automobile Sales)__

Nearly all companies seek to accurately predict future sales of their product(s). If the company can accurately predict sales before producing the product, then they can better match production with customer demand, thus reducing unnecessary inventory costs while being able to satisfy demand for their product.

__3. IMDB Movie dataset Analysis__

