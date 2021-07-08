---
layout: post
title: Predictive Models and Automated Reports Project Reflection
---

In this project, I developed models with a partner to predict the number of bicycle rentals given a set of variables. First, we performed Exploratory Data Analysis, creating several graphs and summary statistics to understand our data better. Then, we fit four separate models - two linear regression, one random forest, and one boosting model - on a training set using cross-validation. We then tested those models on a test set and compared the MSE for each fit. We set up the markdown code to create a different report for each day of the week when knit.

The most difficult part of this project was automating the report to create the reports for each day of the week, but it was straightforward after trying it. If I were to do this project differently, I would incorporate some sort of selection process during the cross-validation for the variables to be included in the linear regression model, rather than just select some random variables of interest.

The big take-away from this project for me is that it is much more efficient collaborating in Github for a team project. In the past, I have attempted to email the files back and forth, or use Google docs to upload each iteration of the file. This was frustrating and time-consuming. Using Github made the workflow much easier and helped me understand why it is so prevalent in data science and programming.

The project is available here: https://cristagregg.github.io/st558_project2/ 
