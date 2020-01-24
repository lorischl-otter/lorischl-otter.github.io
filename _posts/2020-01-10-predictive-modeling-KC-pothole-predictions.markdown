---
layout: post
title: Predictive Modeling - KC Pothole Predictions
date: 2020-01-10 01:00:00 -0600
description: Predictive Modeling in an Interactive Web Application # Add post description (optional)
img: pothole.png # Add image post (optional)
tags: [Models, KC] # add tag
---

Have you ever wondered how long a pothole might take to get filled? If you lived in Kansas City last year, I guarantee you the answer is yes. Through this project, I was able to pull open data from the City of Kansas City, Missouri, and past weather data to create a predictive model (XGBoost regression) to predict how long it would take for a pothole to be filled in the city. I had fun with this project (as you'll see), and appreciated the chance to practice my modeling skills, as well as learn how to create a web app on Heroku for the first time. Take a look [here](http://kc-pothole-predictions.herokuapp.com/)! My GitHub repo for the site and model is located [here](https://github.com/lorischl-otter/pothole-predictions).

Primary Skills used:
* Python
* Feature Engineering
* Linear Regression Modeling (Poisson & XGBoost)
  - Cross Validation and Hyperparamter Tuning
* Model Visualization
  - Permutation Importances
  - Partial Dependence Plots / Interactions
  - Shapley Plots

Skills/Platforms learned specifically for this project:
* Plotly Dash
* Heroku
* CSS

>This modeling project and paired web app were completed as a student project in predictive modeling for the second unit (second month)
of the Data Science track at [Lambda School](https://lambdaschool.com). The goal of the project was to select a dataset, and create and 
explain a predictive model, with an optional extra goal of creating an interactive web app. 
