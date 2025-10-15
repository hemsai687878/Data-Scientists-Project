# Drug Recommender AI App 

***An innovative AI-tool to recommend drugs based on one's attributes***

## Business Problem
I have collected data about a set of patients, all of whom suffered from the same **illness**. During their course of treatment, each patient responded to one of 5 medications, Drug A, Drug B, Drug c, Drug x and y. I will build a model to find out which drug might be appropriate for a future patient with the same illness. The features of this dataset are ***Age, Sex, Blood Pressure, and the Cholesterol of the patients, and the target is the drug that each patient responded to.***

In this project, I'm going to show how to use data science and machine learning knowledge and skills to solve this problem.

## Machine Learning based solution
* **First Step:** I've imported the patient's data set that has attributes about the patient and the most appropriate drug for them.
* **Second Step:** I've analyzed the data by checking its data quality: missing values, outliers, data format, etc. After this, I've visualized the dataset to extract insights about the data.
* **Third Step:** After checking the data quality and visualizing the data set, I've have pre-processed the data set: converted categorical values to numerical values.
* **Fourth Step:** I've have then created two subsets from the orginal data set called:
  * X_train: *Used to train the Machine Learning Models*
  * X_test: *Used to test the performance of the trained models*
  
 * **Fifth Step:** Trained 3 Classifier Models: LGBM Classifier, Bagging Classifier and Decision Tree Classifier model. Checked the trained model's performance using the X_test set.
 
 * **Sixth Step:** Since all the models performed really well and achieved an accuracy score of ***100%***, I chose LGBM classifier model and saved it in the pickle format using joblib.
 
 * **Seventh Step:** Created a front-end app using **HTML and CSS** and integrated the pickle file with the app using the **flask framework**.
 
## Languages Used
* [Python](https://www.python.org/)
  * [PyCharm](https://www.jetbrains.com/pycharm/)
  * [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)
  
* HTML & CSS 

* [Flask Web Framework](https://flask.palletsprojects.com/en/1.1.x/)

## Credits
Thanks to kaggle for providing this dataset.
