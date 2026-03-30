# Modelling and Predicting Cyber Hacking Breaches Using Machine Learning

## Overview
This project focuses on applying machine learning algorithms to detect and predict network security breaches. By analyzing various transmission parameters, the system determines the likelihood of an anomaly or breach, providing a proactive approach to network security.

## Features
* **Exploratory Data Analysis**: Visualizes data relationships using Seaborn heatmaps and countplots to identify critical transmission parameters.
* **Machine Learning Models**: Implements and compares Random Forest, XGBoost, and Logistic Regression algorithms to find the most accurate predictive model.
* **Hyperparameter Tuning**: Uses GridSearchCV to optimize model parameters and evaluate feature importance.
* **Graphical User Interface**: Includes a Tkinter based application that allows users to upload datasets, select specific data rows, and predict network breaches locally.

## Project Architecture
The prediction system follows a distinct workflow:
1. **Data Preprocessing**: Cleaning the dataset by handling missing values and encoding categorical variables using Label Encoding.
2. **Model Training**: Splitting data into training and testing sets, then training the models.
3. **Evaluation**: Comparing models based on training, testing, and cross validation scores. Random Forest is selected as the primary model.
4. **Detection Phase**: Feeding new data through the pre-trained model via the GUI to classify network activity as Normal or Anomaly.

<img width="1004" height="456" alt="image" src="https://github.com/user-attachments/assets/3bca0294-4ceb-4e25-9f05-df5ecd3fa70c" />


## Technologies Used
* **Programming Language**: Python
* **Libraries**: NumPy, Pandas, Scikit learn, XGBoost, Seaborn, Matplotlib
* **GUI Framework**: Tkinter, Pandastable
* **Environment**: Jupyter Notebook

## Usage
1. Open and run `cyber_breaches.ipynb` to execute the data preprocessing, exploratory data analysis, and model training phases.
2. The notebook will generate a serialized model file named `breachmodel.pkl`.
3. Launch the graphical interface by running `MP_GUI.ipynb`.
4. Click **Upload file** to load your testing dataset.
5. Enter the desired row number and click **Predict Breach** to view the prediction result.

## Graphical User Interface

### Breach Prediction App
The main interface allows users to load their test data and predict whether a specific network log is a normal transaction or an anomaly.

<img width="878" height="662" alt="image" src="https://github.com/user-attachments/assets/24e87b02-0add-4507-98c1-fb0fb9e197ae" />

### Data Visualization Window
The application displays the extracted data row using a pandastable view before making the prediction.

<img width="725" height="641" alt="image" src="https://github.com/user-attachments/assets/6b29b666-7e3d-4287-977a-52f6a3434ceb" />
