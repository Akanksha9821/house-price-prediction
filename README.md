
# House Price Prediction Project

## Project Overview
This project demonstrates a machine learning model that predicts house prices using the California Housing Dataset. The model is implemented using Python and popular machine learning libraries such as Scikit-learn. The goal of the project is to build a regression model to predict the median house prices based on features like house age, population, and location.

## Dataset
The dataset used is the California Housing Dataset, which consists of data collected from the 1990 California census. It includes information on:

Median income

House age

Number of rooms and bedrooms

Population

Latitude and longitude of the houses

The target variable is the median house value in California districts.


## Technologies Used
Python: Programming language for implementation.

Scikit-learn: For dataset handling, preprocessing, and model building.

Pandas & NumPy: For data manipulation and numerical operations.

Matplotlib: For basic visualizations .


## Project Structure
house_price_prediction.ipynb: The Jupyter Notebook containing all the code for loading the dataset, preprocessing, training the model, and evaluating its performance.

README.md: This file, providing a summary of the project.


## Model
I used a simple Linear Regression model for this project. The model was trained on 80% of the data, and the remaining 20% was used for testing and evaluating the model's performance.

## Results
The model's performance was evaluated using Mean Absolute Error (MAE), which provides a measure of the average absolute difference between predicted and actual house prices.

Mean Absolute Error (MAE): 0.53 


## How to Run the Project
Clone the repository:

bash

Copy code

git clone https://github.com/Akanksha9821/house-price-prediction.git

Open the Jupyter Notebook (house_price_prediction.ipynb) in your preferred environment (e.g., Google Colab, Jupyter Notebook).

Run the cells to load the dataset, preprocess the data, train the model, and view the results.


## Future Improvements
Experiment with more advanced regression algorithms such as Random Forest or Gradient Boosting.

Perform hyperparameter tuning to optimize model performance.
Add more visualizations to explore the relationships between features and the target variable.
Contributing
Feel free to fork the repository and submit pull requests if you would like to contribute to the project.

## License
This project is open source and available under the MIT License.
