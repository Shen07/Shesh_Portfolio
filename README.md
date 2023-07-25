


## Project 3: POI *(Person of Interest)*
*(Sep 2019 to 2021)*


> **Objective**

 - <p align="justify">The goal of this project is to build a Framework, for segmentation of candidates using machine learning. Which would enable the business team to take decisions such as whether to invest, divest or harvest in candidates based upon the category they fall in.  </p>
 - Over the time, Evolve the framework into a sort of recommendation system.


> **Roles and Responsibilities:**

 1. Coordinating with the stakeholders, SME's and marketing team.
 2. Established a framework based on BCG matrix, with skill and interest as two axes.
 3. Each of these factors *(skill and interest)* are mutually exclusive and so are their data sets.
 4. Market research analysis to gather more data apart from given.
 5. Statistical analysis of the profiles data was done to find correlation between features and determine most significant traits of both the profiles which contributed to their selection or rejection.
 6. Developed a scale for skill-factor and quantified all profiles accordingly.
 7. Interest factor was determined based on surveys, feedback, and engagement on the learning platform.
 8. Data mining of comments, blog post, quizzes followed by text analytics was done.
 9. performed sentiment analysis to classify the text and  each category was separately analyzed further.
 10. Interest scale was developed and the profiles were quantified accordingly 
 11. After the analysis the profiles were plotted on Cartesian co-ordinates with skill and interest as axes to identify clusters across all quadrants.


![](/Images/Candidate_Profile_POI_r.png)
![](/Images/POI cluster.png)


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
|         |precision| recall   | f1-score |  

|--------:|----------:| -------------:|:-------------:|
|Not-Joined| 0.84| 0.76 |0.79
|Joined |  0.89|  0.93 |0.91


![](/Images/RF_JP_Accuracy.png)
![](/Images/AOC_curve.png)
![](/Images/Confusion_matrix_N.png)
![](/Images/JRP_trend.png)






## Project # 1: BMW Financial Services 
***(Jun 2017 - Mar 2018)*** 

>**Roles and Responsibilities:**  

 1. Statistical Analysis of test cases data.
 3. Text analysis to figure out common points of failure.
 4. Detailed Analysis of the tests data and providing insights based on it.
 5. tagging the test cases based on the issue.
 6. Design and develop reporting solutions.


**Note**`: Due to confidentiality and privacy policy of the company, the data shown in some of the images is only for reference and do not represent the actual data in any form. `




>**My other open source ML projects can be found [here](https://github.com/Shen07/MyMLrepo/tree/main)**






