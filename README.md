# Flight Fare Prediction Using Machine Learning ✈

## Overview
 > A Flight price prediction application which predicts fares of flight for a particular date based on various parameters like Source, Destination, Stops & Airline.Data used in this Project is publicly available at Kaggle. The dataset goes through Data Cleaning, Data Wrangling , Exploratory Data Analysis which gives insights about the data and later uses Machine Learning techniques to train the data for prediction. <br/>
  > It is a regression problem which is solved using RandomForestRegressor ML Algorithm which generates accurate results for price prediction. A web application is created using Flask through which user can interact and get accurate prediction of flight fares.
  
  ## Objectives 🏆

In this project, these questions will be answered:

* [x] Does price vary with Airlines?
* [x] How is the price affected when tickets are bought in just 1 or 2 days before departure?
* [x] Does ticket price change based on the departure time and arrival time?
* [x] How the price changes with change in Source and Destination?
* [x] How does the ticket price vary between Economy and Business class?
* [x] Which features have the most impact on predicting flight price?
* [x] Which model is the best for predicting flight price?

<h2>Live Demo</h2>
<p align='center'><img src='https://user-images.githubusercontent.com/69413168/216665107-4b7eb6cc-49d1-4b03-b5eb-36dc98f8c7cf.gif'></p>

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

<h2>Prerequisites :</h2>
<ul>
  <li>Python</li>
  <li>scikit-learn/sklearn</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Jupyter/Spyder/Pycharm</li>
</ul>
<br>

## Dataset 📔

[Kaggle link: Flight Price Data](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)


</details>

## Project Overview 💼

Sample Visualization:

<p align="center">
  <img width="1200" height="400" src="https://github.com/Pegah-Ardehkhani/Flight-Price-EDA-and-Prediction/blob/main/images/airlines.PNG">
</p>

<p align="center">
  <img width="1200" height="400" src="https://github.com/Pegah-Ardehkhani/Flight-Price-EDA-and-Prediction/blob/main/images/airelines_price.PNG">
</p>

Model Evaluation:

<p align="center">
  <img width="1200" height="400" src="https://github.com/Pegah-Ardehkhani/Flight-Price-EDA-and-Prediction/blob/main/images/true_predicted.PNG">
</p>

<p align="center">
  <img width="1200" height="400" src="https://github.com/Pegah-Ardehkhani/Flight-Price-EDA-and-Prediction/blob/main/images/compare.PNG">
</p>


<h2>Model Pipeline :</h2>
<p align='center'><img src='https://user-images.githubusercontent.com/31500911/143293225-c64aa83a-38bf-490a-aacf-eb96eb6c7088.png'></p>

<h2>Result :</h2>
<p align='center'><img src='https://user-images.githubusercontent.com/31500911/144676081-2d692d73-1c16-4c5a-a1ef-0ff50ec576b4.png'></p>


## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt
```

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 


