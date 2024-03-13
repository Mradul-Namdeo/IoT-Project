# IoT-Project

# Details :-
The data (iot_telemetry_data.csv) was generated from 3 identical, custom-built sensor arrays, each connected to a Raspberry Pi device. These IoT devices were placed in different physical locations with varied environmental conditions.

Each IoT device collected 7 readings/features from 4 sensors at regular intervals. The readings include temperature (temp), humidity, carbon monoxide (CO), liquid petroleum gas (LPG), smoke, light, and motion. The data spans from 07/12/2020 00:00:00 UTC to 07/19/2020 23:59:59 UTC, with a total of 405,184 rows of data.

The sensor readings, along with a unique device ID and timestamp, were published as a single message, using the ISO standard Message Queuing Telemetry Transport (MQTT) network protocol.

# Abstract :-
In this project, I extensively explored open-source IoT telemetry data, leveraging machine learning concepts for data analysis. Commencing with the importation of essential libraries, I conducted in-depth data exploration and analysis, addressing data quality concerns through thorough cleaning and visualization. The culmination of the project involved the application of machine learning techniques to derive meaningful insights. This experience enhanced my proficiency in data science methodologies, including data preprocessing, exploratory analysis, and supervised learning, showcasing my ability to extract valuable insights from complex datasets.

# Project Idea :-
1) Conduct time-series analysis on the three IoT devices to identify the most effective device.

Solution :- Shown in Bivariate Analysis

2) Identify which Feature correlates more

Solution :- Shown in Correlation

3) Utilize the collected readings, comprising multiple (7) features, to determine the likelihood of detecting a fire through the presence of light.

Solution :- Shown in Classification

# Dataset Link : 

# COLAB Link : https://colab.research.google.com/drive/1FR2a2gcOQlDHYxnU1xqJks4d7nQmE0R2?usp=sharing
