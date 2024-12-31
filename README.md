# Driver-Battery-Optimization-k-means-clustering

**Project Purpose:**

To develop a clustering model that segments e-vehicle drivers based on their driving behavior and battery usage patterns, enabling customized incentive structures to promote optimal battery usage.

**Business Case:**

Lithionpower, a leading electric vehicle battery rental provider, seeks to enhance battery life and operational efficiency. By grouping drivers based on driving data, the company can implement targeted incentive programs to encourage responsible driving, reducing maintenance costs and improving customer satisfaction.

**Goal:**

Create a machine learning clustering model to identify distinct groups of drivers based on overspeeding, daily distance driven, and other driving factors affecting battery life.

**Deliverable:**

A clustering model with detailed analysis and visualization of driver segments, along with actionable recommendations for incentivizing drivers within each cluster.

# **Data Dictionary**

For the sake of simplicity, you will take only two features such as mean distance driven per day and the mean percentage of time when a driver was more than 5 mph over the speed limit.

Here are what the data represent:

- id: Unique ID of the driver

- mean_dist_day: Mean distance driven by driver per day

- mean_over_speed_perc: Mean percentage of time when a driver was more than 5 mph over the speed limit
