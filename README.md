Title: Crime Prediction Using Classification Algorithms

This repository contains the documents related to the capstone project for course CIND 820 at Toronto Metropolitan University. These documents include the code (ipynb) and html report of the Exploratory Data Analysis for the selected dataset, prepared using the ydata-profiling library in Python; as well as the reports for the different milestones and the general ipynb file showing the commented codes according to the progress in the project.

This project aims to analyze crime occurrences in Toronto from 2014 to 2023, which are included in the database provided by the Toronto Police Service, and build predictive models to predict crime in Toronto. The open database from the Toronto Police Service: https://data.torontopolice.on.ca/datasets/TorontoPS::major-crime-indicators-open-data/about
In this dataset, incidents have been reported since 2014 to date, by time, date, and location – the nearest road intersection node to protect the privacy of parties involved in the occurrence. The Major Crime Indicators (MCI) include Assault, Break and Enter, Auto Theft, Robbery, and Theft Over, excluding sexual violations, homicides, and shootings. 
According to the dataset description, the data collected has been determined through a police investigation as founded, meaning that the offence did occur or was attempted to occur.

The key research questions are: 1) What is the comparative assessment of accuracy among various machine learning classification algorithms, including decision tree, Naïve Bayes and K-nearest Neighbour models, when analyzing crime incidents in Toronto? 2) Which information of a crime occurrence allows for more accurate predictions: the temporal patterns—time of the day, day of the week, or month-- or the spatial patterns-- location, premises, or neighborhood? 3) How the results obtained from this research contribute to understand historical crime patterns and develop a plan with better-targeted interventions to improve community safety.
Data cleaning, pre-processing and features selection is used at some point.

Supervised machine learning methods, such as the decision tree algorithm for classification tasks, is a suitable tool in this database labeled with categorical MCI features. Its performance will be compared with Naïve Bayes and K-nearest Neighbours models. 
