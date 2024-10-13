# Crop Prediction System

## Overview
The **Crop Prediction System** is a machine learning project designed to assist farmers and agricultural planners by predicting the most suitable crops to cultivate based on environmental factors such as soil nutrients, temperature, humidity, and rainfall. This system leverages various classification algorithms to provide data-driven recommendations, thereby enhancing agricultural productivity and sustainability.

## Table of Contents
- [Features](#features)
- [Data Description](#data-description)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [How to Use](#how-to-use)
- [Data Flow Diagram](#data-flow-diagram)
- [Contributing](#contributing)
- [License](#license)

## Features
- Predicts suitable crops based on input environmental conditions.
- Implements multiple machine learning algorithms for comparison.
- Provides visualizations of model performance and accuracy.
- Easy to use with clear instructions for setup and predictions.

## Data Description
The dataset used in this project is the **Crop Recommendation Dataset**, which includes the following features:
- **N**: Nitrogen content in the soil (kg/ha)
- **P**: Phosphorus content in the soil (kg/ha)
- **K**: Potassium content in the soil (kg/ha)
- **Temperature**: Average temperature (°C)
- **Humidity**: Average humidity (%)
- **pH**: Soil pH level
- **Rainfall**: Average rainfall (mm)
- **Label**: Recommended crop type

## Technologies Used
- **Python**: Main programming language for implementation.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib**: For data visualization.
- **Seaborn**: For advanced statistical data visualization.
- **Scikit-learn**: For building and evaluating machine learning models.
- **XGBoost**: For optimized gradient boosting.
- **Pickle**: For model serialization.

## Installation Instructions
To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/shiwanshra1/CROP-PREDICTION.git
   cd CROP-PREDICTION
   ```

2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```

## How to Use
1. Load the dataset by specifying the path to the CSV file.
2. Preprocess the data to handle missing values and select relevant features.
3. Split the dataset into training and testing sets.
4. Train multiple classification models (e.g., Decision Tree, Naive Bayes, SVM, Logistic Regression, Random Forest, XGBoost).
5. Evaluate the models' performance and visualize the accuracy comparison.
6. Make predictions based on new environmental data.

### Example of Making a Prediction
To predict a suitable crop based on specific conditions, define an input array with values for nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall, and use the trained model to predict the crop type.

## Data Flow Diagram
The data flow for predicting crop types includes several key stages:
1. **Data Collection**: Gather relevant agricultural data.
2. **Data Preprocessing**: Clean and prepare the data for analysis.
3. **Data Exploration and Visualization**: Analyze and visualize relationships within the data.
4. **Model Training**: Train classification algorithms on the dataset.
5. **Model Evaluation**: Evaluate models' accuracy and performance.
6. **Making Predictions**: Use the trained model to predict crop types based on new data.
7. **Output**: Display predicted crop types.
8. **Feedback Loop**: Update the model with new data to enhance accuracy.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
