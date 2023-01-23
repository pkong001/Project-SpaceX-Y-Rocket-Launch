# Spacex-Launch-Prediction
##### Please see the data source in notebook file

### Overview
This capstone project's major objective is to foretell if the Falcon 9 first stage will successfully land. SpaceX advertises on their website that their rocket launches cost 62 million while other providers charge upwards of 165 million because they take great pride in being able to reuse the first stage of a rocket launch. The reuse of the first stage is largely responsible for these cost savings. The price of a launch can be calculated if we can know if the first stage will land. If a different business wants to compete with SpaceX for a rocket launch, it may use the information provided here.

This gets us to the main query we are attempting to address: For a specific set of characteristics of a Falcon 9 rocket launch to predict the landing outcomes
![image](https://user-images.githubusercontent.com/112625065/213992954-10eae111-85c6-46de-bc13-706bd7ba0f3d.png)

### Executive Summary
We create a prediction model for the SpaceX Falcon 9 first stage's successful or unsuccessful landing in this capstone project. If we are aware of whether the first stage will land, we can estimate the cost of a launch. To do this, various machine-learning categorization strategies will be employed.
Data collection, data wrangling and preprocessing, exploratory data analysis, data visualization, and machine learning prediction will all be part of the methodology used.The findings of our investigation and analysis suggest that there are some characteristics of rocket launches that are correlated with successful or unsuccessful launches.

The result shows that The Decision Tree may be the best machine-learning algorithm for this task.
![image](https://user-images.githubusercontent.com/112625065/213992986-32c669ae-f0a9-43a5-af52-0bc060b68c32.png)

### Methodology

Data was gathered using two techniques: web scraping launch information from a Wikipedia article and requesting information from the SpaceX API. The data was then transformed and cleaned using the pandas module in Python.
Exploratory data analysis (EDA) was done on the clean data utilizing visualization tools including Python's matplotlib and seaborn packages, as well as SQL queries to provide answers. In order to respond to some analytical queries, interactive visualization packages in Python were employed. Maps were produced using Folium, and interactive data visualizations with Plotly Dash. Perform interactive visual analytics using Folium and Plotly Dash
For the prediction study, four alternative machine learning classification models were employed. The models utilized were decision tree classifier, logistic regression, support vector machines, and k-nearest neighbor. To choose the best model, each one was trained, adjusted, and tested, using suitable evaluators.
![image](https://user-images.githubusercontent.com/112625065/213993152-e780ce7d-9e2a-4639-9696-f84b5a32db60.png)

