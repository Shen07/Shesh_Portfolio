


## Project 3: POI *(Person of Interest)*
*(Sep 2019 to present)*


> **Objective**
<p align="justify">The goal of this project is to build a Framework, for segmentation of candidates using machine learning. It is based on the McKinsey Matrix/BCG matrix. This would enable us to take decisions such as whether to invest, divest or harvest the candidates based upon the category they fall in.</p>


> **Roles and Responsibilities:**

 1. Coordinating of all marketing activities and elements pertaining to it, e.g.: Surveying, campaign design to gather essential data. 
 2. Analyze market trends and the competitive landscape to understand opportunities and potential value.       
 3. Detailed analysis of the data then translation of results of into easily understood presentation materials.
 4. Track key-performance indicators and built a matrix accordingly.
 5. Build a model based on to classify candidates into the categories defined and deploy it as web app.


## Project 2: Joining Predictor 
*(Apr-2018 to Sep 2019)*

> **Objective**
<p align="justify">The goal of this project was to classify the candidates and predict the probability of their joining using machine learning.</p>


>**Roles and Responsibilities:**

 1. Gathered and analyzed the data recruits over past three years(200k+) to look for any patterns, determine the various factors involved and their relative importance.
 2. For further simplification, few of the features were modified and others combined to form a new single feature.***(feature engineering)****
 3. The data was split in a way so as to maintain a balance in number of positives (Joined candidates) and negatives (Candidates who did not Join)
 4. Experimented with DecisionTrees and RandomForest. Since the data mostly consisted of categorical variables. 
 5. Finally decided to go with RF. Also Rf avoid the problem of overfitting and work well with small to medium amount of data.
 7. After several  runs and grid search cross validation, the best parameters which resulted in overall better performance of the the model were determined and the final model was trained on the data.
 8. The model was tuned to varying depth of tree as a hyper parameter.
 9. Opitmized the model exported for use as a REST API.

**Performance metrics**:

|    |precision      | recall   | f1-score |  
|--------:|----------:| -------------:|:-------------:|
|Not-Joined| 0.84| 0.76 |0.79
|Joined |  0.89|  0.93 |0.91


![](/Images/RF_JP_Accuracy.png)
![](/Images/AOC_curve.png)
![](/Images/Confusion_matrix.png)


## Project # 1: BMW Financial Services 
***(Jun 2017 - Mar 2018)*** 

>**Roles and Responsibilities:**  

 1. App testing and Quality Analyst.
 2. Preprocessing and maintaining all test cases data.
 3. Text analysis to figure out common points of failure.
 4. Detailed Analysis of the tests data and providing insights based on it.
 5. Design and develop reporting solutions.
