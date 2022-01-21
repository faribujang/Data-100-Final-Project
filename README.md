# Data-100-Final-Project
Final project for Data 100 at UC Berkeley, using the "Traffic" datasets

**Project Description:**

The project will be split up into two parts: Part 1 and Part 2. We will be releasing Part 1 today and Part 2 at a later date, around Thanksgiving break.

There are three different datasets you can choose from. You will be asked to perform a series of guided analyses to familiarize yourself with the data, and then you will be asked to propose some of your own explorations to be conducted later. That will be done in Part 2, along with some additional questions.

While the three projects are structured very similarly, there are inevitable variations within each dataset that may make certain tasks easier or more difficult on any one of them. We don't want any of you to worry about picking "the hard one." You should choose the dataset that your team finds the most interesting to explore, other considerations aside. We will curve the final results separately within the teams that pick each dataset, and adjust all three grade distributions to reasonably match (mean and variance, modulo not producing grades outside [0, 100]).

Scenario: You're a data scientist at Uber -- sitting in a war room on March 16, 2020, 1 day after California-wide COVID lockdown measures began and the day shelter-in-place measures are announced in the bay area. The entire data science department is on fire: All of your existing traffic models have regressed significantly. Given the sudden change in traffic patterns (i.e., no traffic at all), the company's traffic estimates are wildly incorrect. This is a top priority for the company. Since traffic estimates are used directly for pricing strategies, this is actively costing the company millions every hour. You are tasked with fixing these models.

Takeaways: How do you "fix" models that have learned biases from pre-lockdown traffic? How do you train new ones, with just 24 hours of data? What sorts of data do you examine, to better understand the situation? In the midst of company-wide panic, you'll need a strong inferential acumen to lead a robust data science response. In this project, we'll walk you through a simulated war room data science effort, culminating in some strategies to fix models online, which are experiencing large distributional shifts in data.

**Open-Ended EDA: Understanding lockdown impact on travel times**
Explore daily travel times from Hayes Valley to other destinations both before and throughout lockdown. Use the following questions as suggestions for what to explore, temporally and spatially:

How did lockdown affect travel times? Are there any meaningful factors that determined how travel time would be impacted? How was travel time affected over time?
Travel to which destinations were affected by lockdown? Are there surprisingly disproportionate amounts of impact in certain areas?

**Open-Ended Modeling: Predicting travel time post-lockdown**
This is the real deal and ultimately what Uber cares about. Traffic speeds is a proxy task, but the bottom line and moneymaking machine relies on this travel time estimation. Focus on designing experiments instead of focusing on experimental, quantitative results. Your experiments are successful if they inform a decision, even despite a lower-performing model.

Question 5a
Train a baseline model of your choice using any supervised learning approach we have studied; you are not limited to a linear model.

Question 5b
Improve on your baseline model. Specify the model you designed and its input features. Justify why you chose these features and their relevance to your model's predictions.

Example
Here are potential questions to consider for this part: How does the other variant of your travel times dataset, aggregated across time but reported for all routes, useful? What additional data from the Uber Movement website can you export to better your model?
