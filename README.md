# Conversion rate prediction
This is the repository for the final project of DS 5220 Supervised Machine Learning at Northeastern University. The project was done by Deepak Rao Nadipelly, Ziyue Wang and Pareekshit Reddy Gaddam. 
## Introduction
The aim of this project is to predict the conversion rate for an online retailer based on various item features and other details regarding sales and logistics of the item. Conversions in e-commerce are defined as the number of times that a user completes a desired action on the platform. In this case, the desired action is to purchase a product. Estimating conversion rate is critical for an online retailer as it impacts many aspects of their business. For example, the quality of the recommendations, search results and product advertisements they display to their users. This dataset was taken from a kaggle competition.
Source of the dataset: [Kaggle](https://www.kaggle.com/c/conversion-rate-prediction/data) 
## Guide
The project mainly consists of two part: EDA (Explanatory Data Analysis) and Modeling. To run the code, you need to make sure your local machine meets the requirements presented in `requirements.txt`
## Modeling structure
```
Modeling.ipynb
│   Data Import    
│
└───Data Preprocessing
└───Feature Engineering
└───Utils
└───Modele Buiding
│   └───Data split
│   └───Classical Models
│       │   Logistic Regression
│       │   Naive Bayes
│       │   Random Forest
│       │   Linear SVC
│   └───Boosters
│       │   XGB
│       │   LightGBM
│   └───Neural Network
│       │   Preprocessing
│       │   Modeling
│   └───Model Ensembling
│   └───Model Stacking
│   └───Stepwise regression
```


*Framework inspired by [Weipeng Zhang](https://github.com/Wp-Zhang). Special thanks to him.*
