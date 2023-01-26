# Car-machine-learning-model
Development of a car machine learning model using publicly available data

## Table of contents
- [Webscraping](https://github.com/SuperSalcedo22/Car-machine-learning-model#webscraping)
- [Machine learning](https://github.com/SuperSalcedo22/Car-machine-learning-model#machine-learning-model)
- [Graphical User Interface](https://github.com/SuperSalcedo22/Car-machine-learning-model#graphical-user-interface)
- [Author Info](https://github.com/SuperSalcedo22/Car-machine-learning-model/blob/main/README.md#author-info)

## Webscraping
- After considering several websites, the team decided to utilize [Autotrader](https://www.autotrader.co.uk/)
- [Selenium](https://www.selenium.dev/) used to scrape the data

The variables included were:
- Price
- Mileage
- Body type
- Make
- Model 
- Power
- Engine size
- Year
- Transmission
- Fuel type

Data cleaning was also performed via pandas to ensure the data was of high quality with no null values to affect the analysis

## Machine learning model
- Mean encoding used with one hot encoding to convert categorical variables numerically for the model
- Lasso regression, decision tree and random forest regression trained to find the best model
- Multiple hyperparameters were tuned
   Cross validation
   alpha (for lasso regression)
   number of trees and depth (random forest)
- Random forest regression performed the best with an R2 score of 0.88 and MAE of 19%

## Graphical User Interface
The focus of the GUI was to make it simply and easy to use. This was important because when users are presented with a complex or confusing interface, it makes it more inaccesible and reduces user engagement.

To aid the user, extra bits of functionality were added to enhance the experience:
- kilometre to miles conversion
- PferdStarke (PS) to Brake Horse Power (BHP)
- CC to litres
- Pounds to dollars/ euros conversion using [real time api](https://www.exchangerate-api.com/)
- Error window displaying incorrect inputs and why


## Author info

- [Jan Salcedo](https://github.com/SuperSalcedo22)
- [Pernelle Gamrowski](https://github.com/pernelleg)
- [Tomos Rands](https://github.com/TomosRands123)
- [Callum O'Neill](https://github.com/Rocconeill96)
- [Furqan Akhtar](https://github.com/Furqii)

[Back to top](https://github.com/SuperSalcedo22/Car-machine-learning-model#car-machine-learning-model)
