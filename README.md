# US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification
## Objective:
The objective of this research is to analyze historical accident data to identify patterns and trends in accident occurrence, contributing factors, and potential solutions.
## Dataset Description:
This dataset on traffic accidents covers 49 states of the United States and is continuously updated since February 2016. It is collected through multiple data providers that include various APIs which provide streaming traffic event data. The APIs capture traffic events from different sources such as traffic cameras, traffic sensors in the road network, and law enforcement agencies, among others. Moosavi, Samavatian, Parthasarathy, Teodorescu, et al. (2019) have provided a summary of this process. This large-scale database was created by gathering, integrating, and supplementing data through a comprehensive process. It includes information on 2.8 million traffic accidents that occurred in the contiguous United States. Each accident record contains intrinsic and contextual attributes, such as location, time, weather, natural language description, points of interest, and time of day.
<img width="600" alt="image" src="https://github.com/abdulmahejabeen/US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification/assets/56336879/4a81ec65-19a8-470f-98c9-1474754f68da">


Datasource Link: [US-Accidents (2016 - 2023)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

## Project Objectives:
1. To analyze historical accident data to identify patterns and trends in accident occurrence, contributing factors, and potential solutions.
2. To develop a predictive model that accurately identifies accident-prone areas and helps reduce the frequency and severity of accidents in the USA.
3. To identify the most significant predictors of accidents in the USA, including road conditions, vehicle types, and weather patterns.
4. To explore the use of advanced technologies, such as machine learning and artificial intelligence, to improve the accuracy and effectiveness of accident prediction models.
5. To develop recommendations and guidelines for policymakers, transportation agencies, and other stakeholders to help prevent accidents and reduce their impact on public safety.

## Community Contribution:
Nowadays, car transportation has become an integral part of our daily lives. Considering the persistently high rates of severe accidents and fatalities, it is inevitable to improve automobiles. Regrettably, traffic accidents have always been a part of the driving experience. This highlights the importance of data-driven approaches to road safety and aims to inspire transportation authorities and the public to take action in promoting such approaches.

## Data Preprocessing:
- Datatype Conversions.
- Adding new columns to improve the quality of analysis.
- Identifying and correcting inconsistencies or missing data in the dataset.
- Removing redundant Columns.
- Filling Null Values.
- Label encoding.

## Methods
- Apriori algorithm to provide recommendations based on the association rules.
- Decision tree classifier for severity classification with SMOTE.
- RoBERTa for classifying the severity of the accidents.

## Results:
- Decision tree classifier despite balanced classes done with SMOTE gave a low accuracy of 71% showing that the model couldn't learn how to classify based on the patterns in the data like bumps, crossing, signals, etc. which are the main features in road traffic data.
- The proposed BERT model for solving this problem showed a greater accuracy for very fewer data. With the availability of better computing power and GPU resources, the model can be fine-tuned and better trained with larger data and achieve greater accuracy. It currently gives 85% accuracy in classifying the severity of accidents.

## References:
- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.
- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.
