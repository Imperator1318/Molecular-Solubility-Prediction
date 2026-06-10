## Project Description: Molecular Solubility Prediction

This project focuses on developing machine learning models to predict the logarithm of the aqueous solubility (logS) of molecules based on their molecular descriptors. Accurate prediction of solubility is crucial in drug discovery and chemical engineering.

### **Key Features:**

*   **Data Loading & Preprocessing:** The project begins by loading a dataset containing molecular descriptors and their corresponding logS values. The data is then separated into features (X) and target (Y).
*   **Data Splitting:** The dataset is split into training and testing sets (80% training, 20% testing) using `sklearn.model_selection.train_test_split` with a fixed `random_state` for reproducibility.
*   **Model Training & Evaluation:** Two regression models are implemented and evaluated:
    *   **Linear Regression:** A simple yet effective linear model is trained to establish a baseline performance.
    *   **Random Forest Regressor:** A more complex ensemble model is used to capture non-linear relationships within the data.
*   **Performance Metrics:** Both models are rigorously evaluated using `Mean Squared Error (MSE)` and `R-squared (R2)` scores for both training and test datasets to assess their predictive accuracy and generalization ability.
*   **Model Comparison:** A comparative analysis of the Linear Regression and Random Forest models' performance is conducted using a pandas DataFrame, allowing for easy assessment of their strengths and weaknesses.
*   **Visualization:** The project includes a scatter plot visualizing the relationship between experimental logS values and the predictions made by the Linear Regression model, complemented by a regression line to illustrate the model's fit.

### **Technologies Used:**

*   Python
*   Pandas
*   Scikit-learn
*   Matplotlib
*   NumPy

This project provides a comprehensive workflow for predicting molecular solubility, from data preparation to model evaluation and visualization, serving as a foundational example for cheminformatics and machine learning applications.
