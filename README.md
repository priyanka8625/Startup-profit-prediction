# Startup-profit-prediction

This repository contains a dataset and a Jupyter Notebook (.ipynb file) that demonstrates how to predict the profit of a company using multiple linear regression. The dataset includes information on R&D spend, Administration spend, Marketing spend, and the State of the company. Using this data, the model achieves an accuracy rate of 95.37% on the training data and 89.87% on the testing data.

## Dataset

The dataset `50_startups.csv` contains the following features:
- `R&D Spend`: The amount of money spent on research and development.
- `Administration`: The amount of money spent on administration.
- `Marketing Spend`: The amount of money spent on marketing.
- `State`: The state in which the company is located.
- `Profit`: The profit of the company (target variable).

## Model

The model uses multiple linear regression to predict the profit of the company based on the provided features. The steps involved in the notebook include:
1. **Data Preprocessing**:
   - importing the necessary libraries
   - Encoding categorical data.
   - Splitting the data into training and testing sets.
   
3. **Model Training**:
   - Fitting a multiple linear regression model to the training data.

4. **Model Evaluation**:
   - Evaluating the model's performance on both the training and testing data.
   - Calculating the accuracy of the model.

## Results

- **Training Data Accuracy**: 95.37%
- **Testing Data Accuracy**: 89.87%

## Getting Started

To run the code and experiment with the dataset, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/priyanka8625/Startup-profit-prediction.git
    cd Startup-profit-prediction
    ```

2. **Install the required packages**:
    Make sure you have Python and Jupyter Notebook installed.

3. **Run the Jupyter Notebook**:
    Open the `profit_prediction.ipynb` file in Jupyter Notebook and run the cells to see the code in action.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib

## Happy Learning!
