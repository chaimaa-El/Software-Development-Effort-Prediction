# Software Development Effort Prediction

## Overview
The aim of this project is to design an intelligent model for predicting the development effort of a software project. By analyzing factors such as team size, story points, and velocity, we seek to develop accurate predictive models to estimate the effort required for software development projects.

## Data Import
The project starts by importing the necessary dataset containing information about software projects, including story points, velocity, team size, and effort.

## Data Preprocessing
Before proceeding to model development, data preprocessing is essential. This involves checking for missing values and separating the dataset into training and testing sets.

## Model Development
Three different models are evaluated for predicting software development effort:
1. **K Neighbors Regressor**
2. **Decision Tree Regressor**
3. **Linear Regression**

## Model Evaluation
Each model is trained and evaluated using performance metrics such as accuracy scores, Mean Magnitude of Relative Error (MMRE), and Prediction(25%) indicator. Additionally, feature selection techniques are applied to improve model performance.

## Conclusion
After thorough evaluation, it is concluded that the Linear Regression model performs the best for this problem, providing high accuracy and low MMRE values. However, before feature selection, Linear Regression outperforms other techniques significantly. This suggests the importance of feature selection in model development.

## Technologies Used
- Python
- Scikit-learn
- Jupyter Notebook

## Usage
1. Clone this repository to your local machine.
2. Ensure you have Python and the required dependencies installed.
3. Open the Jupyter Notebook `Software_Development_Effort_Prediction.ipynb` to explore the project.

## Dataset
The dataset used in this project contains information about software projects, including story points, velocity, team size, and effort.


