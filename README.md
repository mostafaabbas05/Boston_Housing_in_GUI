# Boston Housing Project

This repository contains resources and code for analyzing and predicting housing prices in Boston. Below is an overview of the included files and their purposes.

## Files and Structure

### 1. `boston_housing.ipynb`
- **Description**: A Jupyter Notebook containing the code, analysis, and visualizations for the Boston Housing dataset.
- **Usage**: Open this file using Jupyter Notebook or any compatible environment to explore the project's data processing, modeling, and evaluation steps.

### 2. `boston_housing_in_GUI.py`
- **Description**: A Python script that implements a Graphical User Interface (GUI) for interacting with the housing price prediction model.
- **Usage**:
  1. Ensure all dependencies are installed (e.g., `tkinter`, `pickle`, etc.).
  2. Run the script using the command:
     ```bash
     python boston_housing_in_GUI.py
     ```
  3. Use the GUI to input features and get predictions.

### 3. `housing.csv`
- **Description**: The dataset used for training and evaluating the machine learning model. It contains various features related to Boston housing prices.
- **Columns**:
  - **RM**: Average number of rooms per dwelling.
  - **LSTAT**: Percentage lower status of the population.
  - **PTRATIO**: Pupil-teacher ratio by town.
  - **MEDV**: Median value of owner-occupied homes in dollars.

### 4. `model.pkl`
- **Description**: A serialized file containing the trained machine learning model for predicting housing prices.
- **Usage**: This file is loaded in the Python scripts to perform predictions.

## Requirements

Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `tkinter` (for GUI script)

Install the required libraries using:
```bash
pip install -r requirements.txt

## How to Use

### 1. **Exploratory Data Analysis**
   - Open the `boston_housing.ipynb` file in Jupyter Notebook.
   - Run the cells to explore the data and visualize relationships between features.
   - The notebook includes steps for data cleaning, feature engineering, and model evaluation.

### 2. **Run the GUI Application**
   - Use the GUI application to test predictions interactively:
     1. Open a terminal or command prompt.
     2. Run the following command:
        ```bash
        python boston_housing_in_GUI.py
        ```
     3. The application will allow you to input housing features and get predicted prices.

### 3. **Train the Model**
   - If you'd like to retrain the model or experiment with different parameters:
     1. Edit the code in `boston_housing.ipynb` as needed.
     2. Execute the notebook cells to retrain and evaluate the model.
     3. Save the updated model using the `pickle` library.

---

## Dataset

The dataset, `housing.csv`, contains the following features:

- **RM**: Average number of rooms per dwelling.
- **LSTAT**: Percentage of the population with low income.
- **PTRATIO**: Pupil-teacher ratio by town.
- **MEDV**: Median value of owner-occupied homes in dollars.

This dataset is derived from the Boston Housing dataset and serves as the primary resource for model training and evaluation.

---

---

## Conclusion

This project provides a comprehensive framework for analyzing and predicting housing prices using the Boston Housing dataset. By combining exploratory data analysis, machine learning, and an interactive GUI, it serves as an excellent resource for learning and practical implementation. Feel free to explore, modify, and expand upon this work to suit your needs.
