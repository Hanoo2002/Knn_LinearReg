# Machine Learning Assignment

## Problem 1: Classification

### Dataset Description
The MAGIC gamma telescope dataset simulates the registration of high-energy gamma particles in a ground-based atmospheric Cherenkov gamma telescope. The dataset consists of two classes: gammas (signal) and hadrons (background). There are 12332 gamma events and 6688 hadron events.

### Tasks
1. **Class Imbalance Handling:**
    - The dataset is class imbalanced. To balance it, randomly set aside extra readings for the gamma "g" class to make both classes equal in size.

2. **Data Splitting:**
    - Split the dataset randomly into training (70%), validation (15%), and testing (15%) sets. Do not use the testing set during model parameter tuning.

3. **K-NN Classifier:**
    - Apply the K-NN (K-Nearest Neighbors) Classifier to the data.

4. **Hyperparameter Tuning:**
    - Experiment with different k values to find the best results.

5. **Model Evaluation:**
    - Report the accuracy, precision, recall, and f-score for all trained models.
    - Provide the confusion matrix for each model.

6. **Results Analysis:**
    - Add comments on the results and compare between different K-NN models.

## Problem 2: Regression

### Dataset Description
The California Houses prices dataset contains information from the 1990 California census, providing an introductory dataset for regression models. The data includes details about houses in each California district, with columns such as Median House Value, Median Income, Median Age, Total Rooms, Total Bedrooms, Population, Households, Latitude, Longitude, Distance to Coast, Distance to Los Angeles, Distance to San Diego, Distance to San Jose, and Distance to San Francisco.

### Tasks
1. **Data Splitting:**
    - Split the dataset randomly into training (70%), validation (15%), and testing (15%) sets. Do not use the testing set during model parameter tuning.

2. **Regression Models:**
    - Apply linear, lasso, and ridge regression to predict the median house value.

3. **Performance Metrics:**
    - Report Mean Square Error (MSE) and Mean Absolute Error (MAE) for all regression models.

4. **Results Analysis:**
    - Add comments on the results and compare between linear, lasso, and ridge regression models.

