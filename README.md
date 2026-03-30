# Network Breaches Detection

A machine learning project to detect network anomalies and breaches.

## Project Structure

* `cyber_breaches.ipynb`: The primary notebook for Exploratory Data Analysis, data preprocessing, and model training. It uses Pandas, Seaborn, Scikit-learn, and XGBoost.
* `MP_GUI.ipynb`: A Tkinter based Graphical User Interface that loads the trained model and allows users to make predictions.
* `breachmodel.pkl`: The serialized machine learning model.
* `Train_data.csv` and `Test_data.csv`: The datasets used for training and testing the models.

## Requirements

* Python 3.x
* pandas
* scikit-learn
* xgboost
* seaborn
* matplotlib
* tkinter
* pandastable

## Usage

1. Run `cyber_breaches.ipynb` to view the data processing and model training steps.
2. Execute `MP_GUI.ipynb` to launch the GUI application, load the dataset, and predict anomalies using the pre-trained `breachmodel.pkl`.
