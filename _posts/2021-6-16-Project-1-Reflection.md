---
layout: post
title: API Project Reflection
---

In this project I created several functions to access different endpoints from the NHL API. I used these functions to create one "master" function that I could use to call any function and access any endpoint easily. After completing this, I did some Exploratory Data Analysis with data pulled from this API. I created several tables and charts, and got a general understanding of the structure of much of this data. 

The most challenging part of this project was learning how to access the API and comprehend how the data was structured. Accessing the data was simple enough, but I didn't feel like the documentation was helpful, so many of the datasets didn't make much sense to me at first. Additionally, I misunderstood the purpose of the modifiers while building the functions and didn't understand what they were used for. Therefore, I went through a more elaborate process of filtering the data after it was acccessed. 

One thing I would do differently is make sure my naming conventions are consistent from the beginning. Here, I used team_id or franchise_id for filtering the data pulled, depending on which endpoint I was trying to access. However, when I made the wrapped function I realized I needed to go back and make sure everything was named consistently to make it easier for the user to specify what they wanted. It was much harder to go back and change it than it would have been to have it all consistent from the beginning. 

Below is the link to the vignette:
Github Pages: https://cristagregg.github.io/st558_project1  
Github Repo: https://github.com/cristagregg/st558_project1
