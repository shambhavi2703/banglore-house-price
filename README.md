# banglore-house-price
This project is an end-to-end implementation of a machine learning model for predicting house prices in Bangalore, India. The project includes data preprocessing, model building, and a Flask web application for user interface.

<h2>Data Preprocessing</h2>
The data preprocessing and cleaning steps are implemented in preprocess.ipynb notebook. The notebook describes the different steps taken to clean and transform the raw data into a format suitable for machine learning. The cleaned data is saved as ohe_data.csv, which is used in the model building phase.

<h2>Model Building</h2>
The machine learning model is built using the preprocessed data in ML_Model.ipynb. The notebook uses scikit-learn to create a Linear Regression model to predict house prices in Bangalore. The trained model is then saved as 2.pkl.

<h2>Flask App</h2>
The web application is implemented using Flask, a Python web framework. The Flask app is in the app.py file, and it uses the trained machine learning model to make house price predictions. The user interface is created using HTML and CSS, with the index.html file serving as the template.
