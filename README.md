# Flight Fare Prediction Using Machine Learning

## Overview
 > A Flight price prediction application which predicts fares of flight for a particular date based on various parameters like Source, Destination, Stops & Airline.Data used in this Project is publicly available at Kaggle. The dataset goes through Data Cleaning, Data Wrangling , Exploratory Data Analysis which gives insights about the data and later uses Machine Learning techniques to train the data for prediction. <br/>
  > It is a regression problem which is solved using RandomForestRegressor ML Algorithm which generates accurate results for price prediction. A web application is created using Flask through which user can interact and get accurate prediction of flight fares.

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning model to get most out of it. I came to know mathematics behind all supervised models. Finally it is important to work on application (real world application) to actually make a difference.
<br>

<h2>What it does : </h2>
<p align='center'><img src='https://user-images.githubusercontent.com/69413168/216620601-88a31439-70d9-432e-8115-6fec39a1bd20.png'></p>

<h2>Live Demo</h2>
<p align='center'><img src='https://user-images.githubusercontent.com/69413168/216665107-4b7eb6cc-49d1-4b03-b5eb-36dc98f8c7cf.gif'></p>

<h2>How it does : </h2>
<p>Extract the dependent variables and the independent variables from the dataset. Split the skewed data into shuffled sets using stratified shuffle split in sklearn library. Used the Hyperparameter tuning to increase the accuracy of prediction.</p>
<br>

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

<h2>Dataset : </h2>
<ul>
  <li>Airline </li>
  <li>Date_of_Journey</li>
  <li>Source</li>
  <li>Destination</li>
  <li>Route</li>
  <li>Dep_Time</li>
  <li>Arrival_Time</li>
  <li>Duration</li>
  <li>Total_Stops</li>
  <li>Additional_Info</li>
  <li>Price</li> 
</ul>

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


