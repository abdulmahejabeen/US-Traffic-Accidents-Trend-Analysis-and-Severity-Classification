# US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification
## Objective:
The objective of this research is to analyze historical accident data to identify patterns and trends in accident occurrence, contributing factors, and potential solutions.
## Dataset Description:
This dataset on traffic accidents covers 49 states of the United States and is continuously updated since February 2016. It is collected through multiple data providers that include various APIs which provide streaming traffic event data. The APIs capture traffic events from different sources such as traffic cameras, traffic sensors in the road network, and law enforcement agencies, among others. Moosavi, Samavatian, Parthasarathy, Teodorescu, et al. (2019) have provided a summary of this process. This large-scale database was created by gathering, integrating, and supplementing data through a comprehensive process. It includes information on 2.8 million traffic accidents that occurred in the contiguous United States. Each accident record contains intrinsic and contextual attributes, such as location, time, weather, natural language description, points of interest, and time of day.
<img width="600" alt="image" src="https://github.com/abdulmahejabeen/US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification/assets/56336879/4a81ec65-19a8-470f-98c9-1474754f68da">


Datasource Link: [US-Accidents (2016 - 2023)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

## Data Preprocessing:
- Datatype Conversions.
- Adding new columns to improve the quality of analysis.
- Identifying and correcting inconsistencies or missing data in the dataset.
- Removing redundant Columns.
- Filling Null Values
- Label encoding

## Methods
- Apriori algorithm to provide recommendations based on the association rules.
- Decision tree classifier for severity classification with SMOTE.
- RoBERTa for classifying the severity of the accidents.

## Results:
The proposed approach BERT for solving the severity classification of accidents has shown great results of 85% accuracy, especially a perfect F1 score in identifying the fatal
accidents that are considered severity. This proves that intuition of trying the transfer learning of RoBERTa, a generally classification model for Natural Language, can
also work for a specific domain like in this case the accident data.

## References:
- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.
- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.
