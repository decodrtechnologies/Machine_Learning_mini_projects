# Automate Machine Learning Workflows with Pipelines using scikit-learn
## Machine Learning Pipeline:
* For building any machine learning model, it is important to have a sufficient amount of data to train the model. The data is often collected from various resources and might be available in different formats. Due to this reason, data cleaning and * preprocessing become a crucial step in the machine learning project.
* Whenever new data points are added to the existing data, we need to perform the same preprocessing steps again before we can use the machine learning model to make predictions. This becomes a tedious and time-consuming process!
* An alternate to this is creating a machine learning pipeline that remembers the complete set of preprocessing steps in the exact same order. So that whenever any new data point is introduced, the machine learning pipeline performs the steps as defined and uses the machine learning model to predict the target variable.

**This project covers scikit-learn pipelines to automate the machine learning workflow.**

* Refer:https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html

<br>
<p align="center">
<img src="https://2s7gjr373w3x22jf92z99mgm5w-wpengine.netdna-ssl.com/wp-content/uploads/2018/09/WD_3.png" alt="pipeline" width="500" height="300">  
(Source :Western Digital)
</p>
<br>

## Goal:
* Pipelines work by allowing for a linear sequence of data transforms to be chained together culminating in a modeling process that can be evaluated.
* The goal is to ensure that all of the steps in the pipeline are constrained to the data available for the evaluation, such as the training dataset or each fold of the cross validation procedure.

## Libraries Required:
- Scikit-learn

## Steps Involved:
* Import Libraries
* Standardize the data
* Feature Extraction with Principal Component Analysis (3 features)
* Feature Extraction with Statistical Selection (6 features)
* Feature Union
* Learn a Logistic Regression Model

## Dataset Used:
We use PIMA INDIANS DIABETES DATASET
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

The datasets consists of several medical predictor variables and one target variable, Outcome. 
 ```
Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.
```

## License & Reference:
* https://www.kaggle.com/uciml/pima-indians-diabetes-database (CCO Public Domain License)
* Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., & Johannes, R.S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In Proceedings of the Symposium on Computer Applications and Medical Care (pp. 261--265). IEEE Computer Society Press.
