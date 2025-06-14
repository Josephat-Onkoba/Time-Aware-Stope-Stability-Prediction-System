# Stope Stability Prediction System Using Time-Aware Deep Learning
A hybrid deep learning model for predicting underground mining stope stability using both static geotechnical features and time-series sensor data.

# Overview

This project is a prototype implementation of a machine learning system designed to predict the stability risk level of underground stopes in mining environments.

The system uses:

Static geological and engineering features (e.g., rock quality, depth, hydraulic radius)

Dynamic sensor data over time (e.g., deformation rate, seismic activity, stress changes)

It predicts the risk level of each stope as one of the following classes:

    0: Stable

    1: Elevated Risk

    2: High Risk

    3: Unstable

The aim is to help mining engineers identify unstable stopes early and prevent hazardous incidents.

# Model Development
 1. Coming up with datasets - Data collection
 2. Data Preparation 
 3. Data analysis and visualisation
 4. Model selection and training
 5. Evaluating Model Performance
 6. Tuning and Optimizing Your Model
 7. Deploying the Model and Making Predictions
    
 Later we will be Building a user interface to display Stope Healthy Status - connected with our model (our main backend).

 We will be using LSTM model and FeedForward neural network.

 ### 1. Datasets
   a) **Static Stope Features Dataset** - These are geological and design characteristics that don't change over time — recorded once per stope during design.

   b) **Time-Series Dataset Structure** - These are daily sensor readings collected over time (thrice a day window per stope). They represent real-time measurements of physical activity.




