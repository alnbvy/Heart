# The prediction of heart disease
> Machine learning prediction of heart disease

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
- In this project, various machine learning algorithms were utilized to predict heart diseases using clinically gathered data
- The projects contains, feature engineering, data cleaning, data wrangling, exploratory data analysis, visulization and model development.
- Models include: 1) Linear regression, SVM, decision tree, random forest, gradient boosting, Neural Network, etc..
- The heart disease dataset selected for this study consists of 1026 observations. For each observation there are 13 features which describes the patients, their medical symptoms, and various medical test results.
- The results of the seven models run in this study show the strong capabilities of current machine learning technology to form predictions based on datasets. Only the Ridge classification model under-performed. While many of the models relied on similar principals like decision trees their implementations and resources required vary greatly. A neural network model is generally far more complicated to implement than a random forest model with limited advantages on these simple applications. Methods like gradient boosting and random forest models utilize many small weak decision trees to build a strong model. The largest flaw of this study is the ease at which these methods made models with near perfect accuracy. The extremely high results make it difficult to discuss each model’s individual strengths based on the results alone because they hardly differ. When working with exponentially more complex data sets, more advanced models like support vector machines will outperform regular decision trees as available computing power becomes a limiting factor. 

![Example screenshot](ROC.png)
![Example screenshot](Scores.png)
<!-- If you have screenshots you'd like to share, include them here. -->

## Technologies Used
- Python
- SciKit Learn
- Tensorflow
- Pandas
- Matplotlib

## Room for improvement:
- There are several other models that could be used to fit the heart disease dataset, for instance, XGboost. Furthermore, there has been a lot of improvement in the structure of Neural Networks recently. The authors suggest the application of these novel architectures like Cascade feed-forward neural networks, Multi-layer perceptron neural networks, Radial basis neural networks, and Adaptive neuro-fuzzy inference systems.


## Acknowledgements
- The authors are grateful to Dr. Houlong Zhuang for fruitful discussions.


## Contact
Created by [Miralireza Nabavi Bavil, Van McNulty, Amir Tavakkoli and Julie Larsen](anabavib@asu.edu) - feel free to contact me!
