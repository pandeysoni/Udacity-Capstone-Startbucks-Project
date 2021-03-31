# Starbucks Capstone Challenge

## Problem Introduction
Starbucks Offer Dataset is one of the datasets that students can choose from to complete their capstone project for Udacity’s Data Science Nanodegree. The dataset contains simulated data that mimics customers' behavior after they received Starbucks offers. The data is collected via Starbucks rewards mobile apps and the offers were sent out once every few days to the users of the mobile app.

The objective of this project was not defined by Udacity. Thus, I decided to answer few of the questions which came into my mind while looking at the dataset -

Q.1 What offers are popular among all of the users?
Q.2 Which group of people is more likely to use the offer?
Q.3 Which type of offer opt without even noticing the offer recieved?

## Strategy to solve the problem

I used CRISP-DM strategy to solve the starbucks capstone challenge. We have used EDA (Exploratory Data Analysis) for answering the questions which we have talk in Business Understanding step.
I built a machine learning model using logistic regression to address the second part of the question. I hope by building a model that can predict if a customers will waste an offer or not, we can be giving offers with awearness and considerations. The model achived a 71% in both accuracy score and cross-validation score. I also used a confusion matrix. Further details are in my blog post.

## Notebook File
You can find the source code in root directory by this filename Starbucks_Capstone_notebook.ipynb. In this file, you'll see how we have reached to our analysis part and what steps we have followed to reach our goal.

## Other Files
The last two pickel files (firstEvent.pkl, secondEvent.pkl) are two dataframes which took a long time to process during my analysis. They are saved in pickel files so that it only need to be run for 1 time.

## Acknowledgments
I would like to thank Udacity for this amazing project, and starbucks for providing the data.

<a name="getting_started"></a>
# Getting Started

<a name="dependencies"></a>
## Dependencies
* Python 3.5+ (I used Python 3.7)
* Machine Learning Libraries: NumPy, Pandas, Sciki-Learn, matplotlib

## Installing
Clone this GIT repository:
```
git clone https://github.com/pandeysoni/Udacity-Capstone-Startbucks-Project
```

## Activate Virtual environment using python or pyenv
```
# Activate using python
python3 -m venv env
source env/bin/activate
```

```
# Activate using pyenv
pyenv activate venv
```

## Install requirement file
```
pip install requirements.txt
```

## Executing Program:
Run Starbucks_Capstone_notebook.ipynb file in Jupyter Notebook.

## Blog

My Blog post wll summarize the steps which I have taken to achieve this. Here is my [blog post link](https://pandeysoni.medium.com/udacity-capstone-starbucks-project-analysis-f8d771a556a5)

## Authors

* [Soni Pandey](https://github.com/pandeysoni)

