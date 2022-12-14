# CISC451 + CISC452 at Queen's University, Fall 2022 Term

Contains 3 relatively smaller data analytics tasks and 2 ML projects:

### 1. Exploratory Data Analysis on the bus route of Kingston, ON, CA 
We start by analyzing the ‘Transit Data – October’ data collectively to obtain a general understanding about the transit data and how to address the provided 4 questions. Through some simple data cleaning and pre-processing of the ‘Transit Data – October’ data, each team member uses Python or other visualization tools to generate figures related to their assigned questions. Moreover, to further support the answers we arrived, we have researched and analyzed other datasets that contain more geographic information about the bus routes and Kingston resident addresses. Then, by using the Google Map API and Geopandas Python package, we manage to visualize those geographical data interactively.

### 2. Predict patients readmission to the hospital
The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks1. It includes over 50 features representing patient and hospital outcomes.
This is a trinary classification task (3 class labels to predict)

### 3. Unsupervised Customer Segmentation for Online Retail Dataset
Segment the customer into 3 meaningful groups using clustering algorithms on the RFM metrics (Recency, Frequency, Monetary), and clearly identify the main characteristics of the consumers in each segment. Based on the segmentation, a customer-centric marketing strategy can be devised to reach out to different customer types.


## The Binary Classification ML Project: MACHINE LEARNING ON PREDICTION OF H1N1 FLU VACCINATION STATUS OF AN INDIVIDUAL
As a key public health measure to fight against infectious diseases, vaccines provide the immunization for individuals and adequate immunization in a community that can further reduce the spread of diseases through "herd immunity". As the world attentions have all been directed to the COVID-19 vaccines, we are thinking that it may be worth-while to revisit the public health responses to a different recent major respiratory disease pandemic (H1N1) to see if we can reveal some correlations or similarities between the 2 pandemics and determine certain peculiarities from the comparison.

Beginning in Spring 2009, a pandemic caused by the H1N1 influenza virus swept across the world. A vaccine for the H1N1 flu virus soon became publicly available in October 2009. In late 2009 and early 2010, the US conducted the National H1N1 Flu Survey, asking respondents whether they had received the H1N1 flu vaccines or not, in conjunction with questions about themselves. These additional questions covered their social, economic, and demographic background, opinions on risks of illness and vaccine effectiveness, and behaviors towards mitigating transmission. This is the source of the dataset we will use for this machine learning project to thoroughly understand how these personal characteristics or features are associated with the personal vaccination statuses to retrieve insights for the future public health efforts.

Therefore, the problem this project attempts to address can be summarized to using machine learning strategies to predict on whether an individual has received a H1N1 flu vaccine or not based on his/her collected personal characteristics, which can be considered as a binary classification machine learning task.


## The Deep Learning Image Classification Project: Aerial Satellite Segmentation 
Nowadays, drones play an important role in our lives. It can not only be used to take photographs or shoot videos, but also can be used for military, search and rescue. And one of the main technologies of drones is Aerial Semantic Segmentation. It helps drones to do object classification, object detection and segmentation. Moreover, Aerial Semantic Segmentation is also widely used in many critical applications, such as autonomous cars, which is the most popular applications in recent years. Thus, we are interested in this topic and want to know more about it. 

In this project, we will attempt to identify which model is more suitable for the Aerial Semantic Segmentation task. The 4 models in consideration are Simple CNN model, FCN8s+VGG-19, DeepLabV3+ with ResNet101, and the U-Net model. 

Note: CISC451: Topics in Data Analytics, CISC452: neural and genetic computing
