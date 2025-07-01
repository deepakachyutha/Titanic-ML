# Titanic-ML

## Titanic Survival Prediction (KNN Classifier)

This mini project uses the Titanic dataset to explore data preprocessing and apply a simple K-Nearest Neighbors (KNN) model to predict passenger survival.


## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


## Tasks Performed

### 1. Data Visualization
- Created a Age distribution histogram
- Created a Bar chart of survival rate by sex
- Created a Scatter plot of Age vs. Fare

### 2. Data Analysis & Preprocessing
- Handled missing values (`Age`, `Fare`, and `Sex`)
- Converted categorical variables (`Sex`, `Embarked`) into numerical values using `.map()`
- Used `.mean()`, `.mode()` to fill null values and add relavent values

### 3. Machine Learning
- Model used: `KNeighborsClassifier` from `sklearn`
- Features used: `Pclass`, `Age`, `Sex`, `Fare`
- Target: `Survived`
- Accuracy testing using `train_test_split` and `accuracy_score`


## Results

- Achieved basic prediction for survival
- Example: A 19-year-old male, 3rd class, fare 7.25 → predicted outcome (`Not Survived`)
- Accuracy: ~`69.27%`


## Dataset

- **Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- **File used**: `Titanic-Dataset.csv`


## Titanic Model Comparision 

- Three Classifiers are compared - `KNearesKNeighborsClassifier`, `DecisionTreeClassifier` and `RandomForestClassifier`


## Titanic Data Visualization
- Various models like - `Barplot`, `heatmap`, and `pairplot` are used to understand and visualize the data. 

## Dataset License Notice
The Titanic dataset used in this project is publicly available for educational use and is provided by platforms like Kaggle.



*Created by Deepak Battula*