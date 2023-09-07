# ADS-Capstone-IBM
SpaceX Falcon 9 First Stage Landing Prediction. This project is part of the IBM Data Science Certificate. https://www.coursera.org/professional-certificates/ibm-data-science

<p align="center">
  <img width="460" height="300" src="https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/main/GIF%20image.gif">
</p>

# SpaceX Falcon 9 First Stage Landing Prediction
In this project, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website at a cost of 62 million dollars; other providers cost upward of 165 million dollars each, Much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. In this lab, you will collect and make sure the data is in the correct format from an API. The following is an example of a successful launch. This supervised classification project was carried out as part of the IBM Data Science Professional certificate.

# Presentation of the project
The presentation covers all the steps described in Jupyter Notebooks in the following sections: From Data Collection and analysis to prediction of launch success (successful first-stage landing) with classification algorithms We draw a parallel between the SpaceX Falcon 9 and the Arianespace Ariane 5 (and coming Ariane 6) that were dominating the market for commercial launches until SpaceX put an end to this domination thanks to the reusable booster concept and induced cost reduction.
#### <ul>[Presentation - pdf](https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/aae31218a72eae2ea1514cd2f9b7eb3e63dbc5ca/Presentation1.pdf)<ul>

# SpaceX Data Collection.
Request to the SpaceX API. <br>
Clean the requested data.
#### <ul>[ Data Collection - Jupyter Notebook](https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/aae31218a72eae2ea1514cd2f9b7eb3e63dbc5ca/1.%20GH_jupyter-labs-spacex-data-collection-api.ipynb)</ul>

# Data Wrangling 
In this lab, we will perform some Exploratory Data Analysis (EDA) to find patterns in the data and determine the label for training supervised models.

#### <ul>[ Data Wrangling - Jupyter Notebook](https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/aae31218a72eae2ea1514cd2f9b7eb3e63dbc5ca/2.%20GH_labs-jupyter-spacex-Data%20wrangling.ipynb)</ul>

# Web scraping Falcon 9 and Falcon Heavy Launch Records from Wikipedia
Web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled List of Falcon 9 and Falcon Heavy Launches by using Beautiful Soup.
#### <ul>[Falcon9 web scraping - Jupyter Notebook](https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/aae31218a72eae2ea1514cd2f9b7eb3e63dbc5ca/3.%20GH_jupyter-labs-webscraping.ipynb)</ul>

# DA - Understanding Datasets and SQL Queries
Understand the Spacex DataSet
Load the dataset into the corresponding table in a Db2 database.
Execute SQL queries to answer assignment questions
#### <ul>[EDA - Jupyter Notebook](https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/aae31218a72eae2ea1514cd2f9b7eb3e63dbc5ca/4.%20GH_jupyter-labs-eda-sql-coursera.ipynb) </ul>

# EDA Data visualization
EDA Data visualization. Exploring and Preparing Data.
Perform exploratory Data Analysis and Feature Engineering using Pandas and Matplotlib Exploratory Data Analysis.
Preparing Data Feature Engineering
In this assignment, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website at a cost of 62 million dollars; other providers cost upward of 165 million dollars each. Much of the savings is due to the fact that SpaceX can reuse the first stage.
#### <ul>[EDA - Data Visualization - Jupyter Notebook](https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/aae31218a72eae2ea1514cd2f9b7eb3e63dbc5ca/5.%20GH_jupyter-labs-eda-dataviz.ipynb)</ul>

# SpaceX Launch Record Dashboard
Dashboard Application with Plotly Dash about SpaceX launch sites, success rate and payload. In the previous exploratory data analysis labs, you have visualized the SpaceX launch dataset using Matplotlib and Seaborn and discovered some preliminary correlations between the launch site and success rates.

- Launch Site Drop-down Input Component
- Callback function to render success-pie-chart based on selected site dropdown
- Range Slider to Select Payload
- Callback function to render the success-payload-scatter-chart scatter plot.
  
##### Note: The interactive Notebook doesn't work on GitHub. Must be downloaded and executed locally. Or on Google Colab.
#### <ul>[Dashboard - Jupyter Notebook](https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/aae31218a72eae2ea1514cd2f9b7eb3e63dbc5ca/6.%20GH_Build_a_Dashboard_Application_with_Plotly_Dash.ipynb)<ul>

# Launch Site Location Analysis with Folium
Interactive The launch success rate may depend on many factors, such as payload mass, orbit type, and so on. It may also depend on the location and proximities of a launch site, i.e., the initial position of rocket trajectories. Finding an optimal location for building a launch site certainly involves many factors, and hopefully, we can discover some of the factors by analyzing the existing launch site locations.

In this lab, you will be performing more interactive visual analytics using Folium.


##### Note: The interactive Notebook does not work on GitHub. It must be downloaded and run locally, with an Anaconda distribution, for example. Or on Google Colab.
#### <ul>[Launch sites - Folium](https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/aae31218a72eae2ea1514cd2f9b7eb3e63dbc5ca/7.%20GH_lab_jupyter_launch_site_location.ipynb)<ul>

# SpaceX Launch Success. Machine Learning classification
Machine Learning Prediction using Classification Algorithms: KNN, Decision Tree, SVM, Logistic Regression.
Optimization of hyperparameters.

#### <ul>[Machine Learning - Jupyter Notebook](https://github.com/SSIDGIT/ADS-Capstone-IBM/blob/aae31218a72eae2ea1514cd2f9b7eb3e63dbc5ca/8.%20GH_SpaceX_Machine%20Learning%20Prediction_Part_5_v8_shuffling.ipynb)<ul>
<br>
<br>
<br>

