# Spacex-Launch-Prediction
##### Please see the data source in notebook file

### Overview
This capstone project's major objective is to foretell if the Falcon 9 first stage will successfully land. SpaceX advertises on their website that their rocket launches cost 62 million while other providers charge upwards of 165 million because they take great pride in being able to reuse the first stage of a rocket launch. The reuse of the first stage is largely responsible for these cost savings. The price of a launch can be calculated if we can know if the first stage will land. If a different business wants to compete with SpaceX for a rocket launch, it may use the information provided here.

This gets us to the main query we are attempting to address: For a specific set of characteristics of a Falcon 9 rocket launch to predict the landing outcomes

### Executive Summary
We create a prediction model for the SpaceX Falcon 9 first stage's successful or unsuccessful landing in this capstone project. If we are aware of whether the first stage will land, we can estimate the cost of a launch. To do this, various machine-learning categorization strategies will be employed.

Data collection, data wrangling and preprocessing, exploratory data analysis, data visualization, and machine learning prediction will all be part of the methodology used.

The findings of our investigation and analysis suggest that there are some characteristics of rocket launches that are correlated with successful or unsuccessful launches.

The result shows that The Decision Tree may be the best machine-learning algorithm for this task.

### Methodology

Data was gathered using two techniques: web scraping launch information from a Wikipedia article and requesting information from the SpaceX API. The data was then transformed and cleaned using the pandas module in Python.
Exploratory data analysis (EDA) was done on the clean data utilizing visualization tools including Python's matplotlib and seaborn packages, as well as SQL queries to provide answers. In order to respond to some analytical queries, interactive visualization packages in Python were employed. Maps were produced using Folium, and interactive data visualizations with Plotly Dash. Perform interactive visual analytics using Folium and Plotly Dash
For the prediction study, four alternative machine learning classification models were employed. The models utilized were decision tree classifier, logistic regression, support vector machines, and k-nearest neighbor. To choose the best model, each one was trained, adjusted, and tested, using suitable evaluators.

### Result

You can view the result in ssssss


### Conclusions

The Decision Tree Classifier is the most accurate predictive model for this dataset, having a 94% accuracy rate.

The analysis revealed that as the success rate has increased over time, there is a positive correlation between the number of flights and the success rate.

The launch sites are placed at a safe distance from cities but strategically close to roads and railroads for the transit of people and goods.

Payload mass can be related to success rate since lighter payloads have typically had better results than bigger payloads.

The SSO orbit has a success rate of 100%.


* Please see futher explanation in full [presentation](https://github.com/pkong001/Project-SpaceX-Y-Rocket-Launch/blob/main/1-Pongpisut_Space_presentation.pptx)




