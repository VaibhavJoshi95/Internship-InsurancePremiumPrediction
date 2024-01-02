# Insurance Premium Prediction



## Table of contents
* [Demo](#demo)
* [Overview](#overview)
* [Project Goal](#project-goal)
* [Technical Aspects](#technical-aspects)
* [Installation](#installation)
* [Feature Request](#feature-request)
* [Used Technologies](#used-technologies)
* [Appendix](#appendix)
* [FAQ](#faq) 
* [Author](#author)


## Demo
• Link for web application : http://insurancepremiumprdiction-env.eba-2rchbbjc.eu-north-1.elasticbeanstalk.com/predict



## Overview
Nowadays, health is one of theprimary priority for everyone, and the cost of treatment is a source of stress for anyone who has to deal with it on a daily life. Th The new diseases in the market is making it more worse.

The goal of this project is to build a prediction model using multiple machine learning
techniques and to use a template to document the end-to-end stages. We're trying to
predict the expenses an individaul has to do on insurance premium, which is a regression issue.

The dataset contains about 13k records and 6 features which after all the implementation of all standard techniques like Data Cleaning, Feature Engineering, Feature Selection, etc was feeded to our Classifier which after training and testing, was deployed in the form of a web application.
## Project Goal
This complete project is made as a part of Data Science Internship at [iNeuron.ai](https://internship.ineuron.ai/).
## Technical Aspects
The whole project has been divided into three parts. These are listed as follows :

• 	𝐃𝐚𝐭𝐚 𝐏𝐫𝐞𝐩𝐚𝐫𝐚𝐭𝐢𝐨𝐧 : This consists of extracting data from source and utilizing it, Data Cleaning, Feature Engineering, Feature Selection, EDA, etc.

• 	𝐌𝐨𝐝𝐞𝐥 𝐃𝐞𝐯𝐞𝐥𝐨𝐩𝐦𝐞𝐧𝐭 : In this step, we use the resultant data after the implementation of the previous step to cross validate our Machine Learning model and get the perfect regression model in order to make our model predict as accurate results as possible.

• 	𝐌𝐨𝐝𝐞𝐥 𝐃𝐞𝐩𝐥𝐨𝐲𝐦𝐞𝐧𝐭 : This step include creation of a front-end using html, Flask and AWS to put our trained model into production.
## Installation
The Code is written in Python 3.8. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:
```bash
pip install -r requirements.txt
```
Run on your Local Machine :

```bash
python application.py
```
This will start the run the application.py which will connect our ML model to AWS cloud to run our server continuously.
## Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly email me (vaibhavgjoshi95@gmail.com) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue here. Please include sample queries and their corresponding results.
## Used Technologies
![Logo1](https://www.vnurture.in/wp-content/uploads/2021/06/python.png)

## Appendix
Link for video regarding to the explanation of the project :  
https://drive.google.com/file/d/1mZZ5MC4XlN1SfEYY6fTsfdibw82kteBD/view?usp=sharing

Link for App Documentation :    
https://github.com/VaibhavJoshi95/Internship-InsurancePremiumPrediction/tree/main/Documents


## FAQ

#### What is the source of data?

Dataset link : 
https://www.kaggle.com/datasets/noordeen/insurance-premium-prediction


#### What techniques were you using for data pre-processing?
* Removing unwanted attributes
* Visualizing  relation of independent variables with each other and output variables
* Checking and changing Distribution of continuous values
* Cleaning data and imputing if null values are present. 
* Converting categorical data into numeric values.
* Scaling the data

#### How training was done or what models were used?

Data pipeline was created to implement data scaling, Ordinal encoding and an estimator to prevent any data leakage. 
GradientBoost model was used as the best estimator which was then used for production. 

#### What are the different stages of deployment?

* The code was first committed on Git hub. The pipeline was created between Git and AWS. Then the code was deployed to the AWS.


## Author

 [Vaibhav Joshi](https://www.linkedin.com/in/vaibhav-joshi-a474a014b/)