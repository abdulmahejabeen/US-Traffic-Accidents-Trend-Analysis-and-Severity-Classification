# US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification
## Objective:
The objective of this research is to analyze historical accident data to identify patterns and trends in accident occurrence, contributing factors, and potential solutions.
## Dataset Description:
This dataset on traffic accidents covers 49 states of the United States and is continuously updated since February 2016. It is collected through multiple data providers that include various APIs which provide streaming traffic event data. It is collected through multiple data providers that include various APIs which provide streaming traffic event data. It is the collection of car accident data from various sources such as MapQuest and Bing. 

The data set contains 47 features, some features include TMC, which is a Traffic Message Channel code, Severity, which is a number ranging from 1 to 4 indicating the extent
of the impact on traffic and the level of damage or fatalities; and Description, which provides a natural language description of the accident, and Weather Condition, which describes the weather at the time of the accident using natural language keywords.

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
