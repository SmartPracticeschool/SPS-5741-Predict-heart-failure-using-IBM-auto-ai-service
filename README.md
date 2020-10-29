# SPS-5741-Predict-heart-failure-using-IBM-auto-ai-service

##### Project Output (Node-RED App) URL:
https://sps-5741-predict-heart-failure-using-ibm-auto-ai-service.eu-gb.mybluemix.net/ui

##### Project Demonstration Video Link:
https://www.youtube.com/watch?v=a8coQHwPUY4
https://drive.google.com/file/d/1JLCe29TAbhQ38l6G87p63MiZUfLsEpHo/view?usp=sharing


![Project Tittle](/Images/Tittle_Design.jpg)

### Objective:
The Objective of this project is to predict probability of patient expected heart failure based on his/her details. I implemented Gradient Boosting Classifier model using IBM Auto AI and Machine Learning Service to predict the Heart Failure and its probability value. I build the Node-RED Web App.


### The repository is a learning exercise to:
1.	Apply the fundamental concepts of machine learning from an available dataset.
2.	Evaluate and interpret my results and justify my interpretation based on observed data set.
3.	Create notebooks that serve as computational records and document my thought process.
4.	Identifying the problem and Data Sources.
5.	Pre-Processing the Data.
6.	Exploratory Data Analysis.
7.	Build the model based on Gradient Boosting Classifier to predict whether the patient get heart failure or not.



### Project Description: 

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide.
Heart failure is a common event caused by CVDs and this dataset contains 9 features that can be used to predict mortality by heart failure.

In this project, you need to build a model using Auto AI and build a web application where we can get the prediction of heart failure.

#### Services Used:

1.	IBM Watson Studio
2.	IBM Watson Machine Learning
3.	Node-RED
4.	IBM Cloud Object Storage

### Architecture:

![Project Architecture](/Project_Architecture.png)
 


### Steps to be followed to build this project:

1.	Create a project in IBM Watson Studio – Predict Heart Failure.
2.	Add Auto AI experiment.
3.	Create a Machine Learning instance.
4.	Associate ML instance to the project.
5.	Load the dataset to cloud object storage.
6.	Select the target variable (HEARTFAILURE parameter) in the dataset
7.	Train the model.
8.	Deploy.
9.	Build web application using Node-Red.

### Sample Output:
 
![Output](/Node-RED-App-Output(Y).jpg)
