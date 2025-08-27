# Titanic-ML

## Titanic Survival Prediction 

### Project Overview

This project presents a complete machine learning workflow to predict passenger survival on the Titanic. . The goal was to go beyond a basic model and demonstrate a data-driven approach, from initial exploratory analysis and data cleaning to a comparative evaluation of multiple classification algorithms to identify the most effective model. 

### Methodology

The project was broken down into three key phases:

1.  **Data Visualization & Analysis:**
    * Performed a comprehensive Exploratory Data Analysis (EDA) to understand the dataset's structure and uncover key relationships between passenger attributes (like class, sex, and age) and survival rates.
    * Created several visualizations, including correlation heatmaps and bar charts, to inform feature selection and preprocessing strategies.

2.  **Data Cleaning & Preprocessing:**
    * Executed robust data cleaning procedures, handling missing values in `Age`, `Fare`, and `Embarked` with mean/mode imputation to ensure a complete dataset for modeling.
    * Transformed categorical features like `Sex` and `Embarked` into numerical formats to make them compatible with machine learning algorithms.

3.  **Model Training & Comparison:**
    * Trained and evaluated three distinct classification models to find the best predictor for this task:
        * K-Nearest Neighbors (KNN)
        * Decision Tree Classifier
        * Random Forest Classifier
    * Rigorously tested each model on unseen data to ensure the results were generalizable and reliable.

### Results

The Random Forest Classifier delivered the highest accuracy, demonstrating the strength of ensemble methods on this dataset.

| Model                    | Accuracy |
| ------------------------ | :------: |
| K-Nearest Neighbors      |  72.22%  |
| Decision Tree Classifier |  77.78%  |
| **Random Forest Classifier** | **81.11%** |

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## Dataset

- **Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- **File used**: `Titanic-Dataset.csv`


## Titanic Model Comparision 

- Three Classifiers are compared - `KNearesKNeighborsClassifier`, `DecisionTreeClassifier` and `RandomForestClassifier`


## Titanic Data Visualization
- Various models like - `Barplot`, `heatmap`, and `pairplot` are used to understand and visualize the data. 

### How to Run

1.  Clone the repository.
2.  Ensure you have the required libraries installed (`pandas`, `matplotlib`, `seaborn`, `scikit-learn`).
3.  Open and run the Jupyter Notebooks (`Titanic.ipynb`, `TitanicModelComparision.ipynb`, `TitanicVisualization.ipynb`) to see the full analysis and model training process.

---

## Dataset License Notice
The Titanic dataset used in this project is publicly available for educational use and is provided by platforms like Kaggle.

---
*Created by Deepak Battula*