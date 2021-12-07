# Project repository for MLOps Project
# Prediction of Airline Customer Satisfaction

This is a repository containing all files and information of the project **Prediction of Airline Customer Satisfaction** which was undertaken as part of the *MLOps and ML System Design* course during Term 5 (2021) at the Indian Institute of Management, Bangalore. The project was completed under the guidance of  Prof. Manaranjan Pradhan.

> Project Status: **COMPLETED**

## Objective:
The objective of this project was to predict satisfaction of customers of an Airline who had various levels of experience with different aspects of the travel/airline. The results of this project are intended for use by the airline's internal staff to assess the satisfaction of their customers and take preventive/corrective measures.

## Procedure:
1. Data Profiling
2. Exploratory Analysis & Feature Engineering
3. Initial model exploration with H2O's ***AutoML***
4. Experimenting with the suggested models from AutoML but with different encodings, etc.
5. Model deployment as an *Interface* with the help of ***Gradio***
6. Model Monitoring and Explainability

## Tools and Technologies:
1. [Python](https://www.python.org/) and related packages (numpy, pandas, scikitlearn, seaborn, matplotlib, etc.)
2. [Weights and Biases](https://wandb.ai/site) for experiment tracking
3. [Google Colaboratory](https://colab.research.google.com/)
4. [Gradio](https://gradio.app/) for interface development

## Problem and Dataset Overview:
The dataset we have taken for predicting ASD syndrome consists of 1054 children in the age group of 12-36 months. Out of the 1054 observations, there are a total of 728 positive class (i.e., children having ASD traits and requiring further medical care). There are a total number of 18 variables (including the output variable). The remaining variables are of categorical nature and form the crux of the dataset. The categorical variables which make up the bulk of total variables, namely A1-A10, are subjective behavioural questions that have been answered about the children’s emotional development.

Dataset : [Airlines Dataset | Kaggle](https://www.kaggle.com/sjleshrac/airlines-customer-satisfaction)

Task: Classification

Attribute Type: Numerical(nominal and ordinal) and categorical

Area: Hospitality

Format Type: Standard Data Matrix

Number of Instances (records in the dataset): 129,880

Number of Attributes (fields within each record): 22 + 1


## Attribute Information:
Attribute Type: Description
TBD

## Getting Started:
NOTE: The notebooks in this repo all have links that enable running it on Google Colaboratory but it is designed to be cloned to local system and then used. If running on Colab, please follow instructions in each notebook as to how the data must be loaded. All else remains the same in both methods.
1.  Clone this repo by :
```python
git clone https://github.com/rk2896/MLOps_project.git
```
(for help in other methods of cloning, see this [tutorial](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository))

2.  ```pip install requirements.txt``` to get the exact environment this project has been developed on, including all dependencies and sub-dependencies. NOTE: The *requirements.txt* file in this repo contains all the packeges used in this development environment along with all the dependencies. Use with caution. 
> Alternatively, you can pip install the required packages as and when needed by following the instructions on the respective notebooks. **RECOMMENDED** since this helps reduce clutter in the environment.

3.	All data can be found in [*./data*](https://github.com/rk2896/MLOps_project/tree/main/data) folder
4.	All models can be found in [*./models*](https://github.com/rk2896/MLOps_project/tree/main/models) folder in various formats
5.	For deployment, Gradio URI's are active for **72 hours** upon creating. If the URI shown below the cell does not work, rerun the notebook and use the new URI
6.	All the reports, including data profile report, experiment tracking reports and model cards are present under the [*./reports*](https://github.com/rk2896/MLOps_project/tree/main/reports) folder


## References:
TBD

## The Team:
1. Rahav Manoharan [GitHub](https://github.com/rahav-manoharan)
2. Radha Krishnan SE [GitHub](https://github.com/rk2896)
3. Harshit Dutt [GitHub](https://github.com/harshitdutt47)

Please feel free to contact the team with any questions or if you are interested in contributing!