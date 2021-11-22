# Titanic
This dataset has passenger information who boarded the Titanic. The Titanic sank after colliding with an iceberg. The dataset includes information like survival status, Class, Fare, and other variables. 

### Goal
The goal of this repository is to predict survival of passengers using Supervised Machine learning Techniques inluding HyperParameter Tuning to optimise the accuracy scores of the models.

This project addresses the following Data Analysis topics:

#### Data Exploration and Preparation- 
Learn about the dataset: 
- Is there missing data?
- Is it categorical/ordinal? 
- Checking distributions of independent features

#### Data Visualization and Presentation-
- Plotting relational heatmaps of features against survival
- plotting various distribution graphs to check for any skewness

#### Data Representation and Transformation-
- Droping some of the columns which many not contribute much to our machine learning model such as "Ticket No"
- Filling in missing values using median/mean values
- Encoding features into ordinal values,
- Applying Under/Oversampling technique since the dataset is imbalanced
- Split data into train and test sets
- Initialize Machine Learning algorithms
- Hyperparameter Tuning with Grid Search and RandomCV
- Prediction

## Findings:
- The Gradient Bosting Classifier seems to be the best classifer with the highest accuracy score (84%). However, we can notice that there was an overfit in the traning set which was reduced after hyperparameter tuning.
- Although the accurracy scores for both the Gradient Bosting Classifier & RandomForest Classifier are the same, it is important to note that the Gradient Bosting Classifier had a higher Average accuracy score (81%) compared to the RandomForest classifer. 

## Future Work
- The Name feature could be split as per the Name title to check on any difference in survival 


# Installation and Usage 
Fork/Download this project and run the 



# Libraries/Dependencies 
## Visualisation 
- Seaborn 
- Matplotlib 
## Analysis 
- Scikit Learn
## Data 
- NumPy 
- Pandas 
## Tools/Environments 
- Jupyter 
- Python3









