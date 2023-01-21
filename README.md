# Flask_Deployment
This project is using a Random Forest Classifier from the sklearn library to train a model on the titanic dataset,
using features like Pclass, SibSp, Parch, and Fare to predict whether a passenger would survive or not. 

The trained model is then pickled and loaded in a Flask web application,
which takes user inputs for the same features and returns the prediction of survival. 

The HTML template is rendered using Jinja2 template engine to provide a UI for user inputs and displaying the prediction.
