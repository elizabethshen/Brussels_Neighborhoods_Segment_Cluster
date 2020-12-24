## Methodology and Analysis

### Methodology

In this project, we will analyze the different neighborhoods of Brussels, and try to find which neighborhoods are the best matches for the expats in Brussels. 

We need identify the key concerns from expats point of view and to establish the most important criteria they apply when choosing a neighborhood to live in.

In the first step, we collected the Location data of the 19 municipalities in the Brussels Region.

We also collected location and category data [the most common avenues of different neighborhoods] from FourSquare.

The Second step is the Exploratory Analysis, including to cluster and segment the neighborhoods.

We used different Statistics, One-Hot Coding, K-Means machine leaning, and different Visualization Tools, like Folium Maps with clusters and Choropleth Map, to help us tocluster, segment, and visualize the neighborhoods.

The final step is to analyze and categorize the different neighborhoods in the Brussels region. We joined different data, and segmented the neighborhoods into different categories based on the key criteria related to choosing a neighborhood to live in.

### Application examples:

***Json File***: Since all the relevant data is in the [feature] key of [ Fourth level Administrative Divisions of the Brussel], we cleaned and reduced the data and to define a new variable that includes this data.

***Folium Map***: We used Folium map intensively to show the different neighborhoods segments, and we also used the Choropleth map to produce the Brussels' neighborhood crime rate map.

***Four Square API***: To get [the most common venues] in different neighborhoods in the Brussels Region.

***Machine Leaning***: K-Means: We run the best K analysis with [elbow method] and it shows the K=3 is the optimum k of the K-Means

Others: We used [geopy library] to get the latitude and longitude values of the 19 municipalities of Brussels.
