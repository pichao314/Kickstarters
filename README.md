# Kickstarters

## Description

Kickstarter is a famous public-benefit corporation based in New York City that helps entrepreneurs crowdfunding on creative projects. Since people can get a chance to start their business by backing successful Kickstarter project, this platform has grown tremendously in the past few years. Whereas, the hard truth of doing business is that not every entrepreneur will get enough funding to launch their projects in the end. In order to find what contributes to a project’s success, we plan to analyse a dataset with different features of pledged projects from the Kickstarter platform and compare the contribution and effect of each attribute. 

Our proposed project will be building a classification system that tries to figure out the commonality of those successful projects and predict the success of other currently pledged projects. Our model will be able to give a classification of the tested project if it is worth people to back it up. This project will be separated into two parts in order to build our classification model: 1) data description analysis 2) model prediction analysis. The possible choice of models are decision trees, random forests, SVM, Logistic Regression, KNN and etc. We will make analysis of each model’s performance and hence giving a conclusion of the “winning” solution at the end.
Dataset to be used:

## Datasets
Kickstarter: https://www.kaggle.com/wood2174/mapkickstarter#MasterKickstarter.csv

The dataset is 56 MB that has 99,000 records of Kickstarter projects range from 2009 to 2017. There is a total of 57 attributes for each records that representing the projects’ origin, title, description, pledged amount and launch duration and etc. Not all the attributes in this dataset are useful and will be preprocessed in order to produce a satisfactory result for our project.

## Required Package Version

- ipython (7.9.0)
- matplotlib (3.1.1)
- numpy (1.17.4)
- pandas (0.25.3)
- scikit-learn (0.21.3)
- scipy (1.3.2)
- seaborn (0.9.0)
- wordcloud (1.5.0)

## Running Instruction

- Place the dataset on the parent folder or change the direction in the source code to run the code
- Make sure the package is correctly installed with specified or above versions
- The code is tested with Windows 10 Pro 1909, macos catalina, ubuntu 18.04.3 LTS
