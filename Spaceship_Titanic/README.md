# Feature Engineering and Model Building

**Objective**

The goal of this assignment is to build a predictive model from the [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic) dataset on Kaggle, which will be evaluated based on its performance on the provided test set (leaderboard). 
Note, your task is to build a model that uses **only four** features from the original dataset and **four additional** engineered features. One-hot or other categorical-to-numerical encodings are counted as one feature. The final model should use only these eight feature encodings to predict whether a passenger was transported to an alternate dimension.

Kaggle provides a starter script for this competition [here](https://www.kaggle.com/code/gusthema/spaceship-titanic-with-tfdf/notebook).

**Tools and Platform**

You can use any tool or platform for this analysis. However, a final notebook needs be created on the Kaggle platform that loads and pre-processes the data, builds the final model using the 8 feature encodings, and writes a submmsion file with predicitons for the test set.

**Dataset**

The Spaceship Titanic dataset contains data about passengers who are onboard the spaceship Titanic, which mysteriously transported half of its passengers to another dimension during its maiden voyage. The data includes multiple features related to each passenger.

**Features**

You are allowed to use only four features from the original dataset.

You must engineer four additional features which can be derived from the data provided or by external means as long as all external data sources are freely accessible and reproducible.

One-hot or other categorical-to-numerical encodings are counted as one feature.

## Assignment Steps

**Data Exploration**

Begin by exploring the dataset provided to understand the various features and the target variable.

**Feature Selection**

Choose four original features from the dataset that you believe will be most helpful in predicting the target. Justify your selections. Be rational (use feature selection algorithms, use them wisely..).

**Feature Engineering**

Engineer four new features. These could be interactions, aggregations, or transformations of the original data. Show what the new features contribute.

**Data Preprocessing**

Apply necessary pre-processing steps to the selected and engineered features, such as handling missing values, scaling, and encoding. One-hot or other categorical-to-numerical encodings are counted as one feature.

**Model Building**

Construct a predictive model using any machine learning algorithm. Justify your choice of algorithm and explain your model configuration.

**Model Evaluation**

Split the original data into training and validation sets to evaluate the performance of your model.

Discuss the metrics used for evaluating the model performance.

**Submission File Creation**

Use your model to make predictions on the test set.

Generate a submission file in the format specified by the competition.

**Documentation**

Throughout your notebook, include detailed comments and explanations of your code and thought process.

Conclude with a summary of your findings and model performance.

**Submission**

Ensure your notebook runs from top to bottom without errors to generate the final submission file.

Set the notebook to public on the due date for leaderboard evaluation.

**Evaluation Criteria**

Correctness and completeness of the code.

Quality and creativity of the feature engineering.

Clarity and depth of the analysis and explanations.

Performance of the model on the test set (as per the leaderboard).

**Deadline**

TBA

This assignment will not only test your ability to handle real-world datasets but also your creativity in feature engineering and your proficiency in building effective models. Good luck!
