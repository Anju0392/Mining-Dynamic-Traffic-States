# Mining Dynamic Traffic States Over Large Road Network from Big Data

### Objective
The study proposes a data mining technique to identify the traffic pattern over various locations in Brisbane based on historical data. This study analyses the traffic flow based on the average travel time between two sensors to identify the travel path of vehicles or the path which takes more time to travel for traffic optimization. The result of the study allows the traffic department authorities to understand how the travel time varies

### Data Used
Queensland Government open data portal provided the traffic datasets, gives information about the Average Travel Times for key priority routes (links) on the state-controlled road network (Brisbane data). 

### Approach
#### Exploratory Data Analysis
An exploratory data analysis is performed to visualize the data points and to analyze how the data are distributed. Based on the data travel time Vs INTERVAL_END.

#### Cluster Analysis
A clustering analysis is performed for this study, which group of objects which are like each other and group the different object. By performing the clustering technique, the optimum number of clusters obtained based on the data is 6 and then build a clustering model based on the optimum number of clusters.

### Finding & Result
The below is an analysis of the study @ 7.00am (as an example) in the morning. It says that,the travel time profile at 7.00 AM for every link in each cluster. The clusters with a high travel time show the link which has heavy traffic during the morning at 7.00 AM.
![image](https://user-images.githubusercontent.com/48005554/161477369-7b45a3cb-332d-4724-838f-5ba28852c8d9.png)

The sensors that show a larger travel time states that there is higher traffic congestion. Thus, the identification of travel time profile at various time interval across the entire road network helps the traffic authorities to analyze and optimize the configurations of the road network in reducing traffic congestions, so city development decisions can be made in a better way which ultimately helps the road users to plan their trip.

