# Cycling Incidents Seattle WA

### Problem Statement

Using feature of an incident predict the severity of the incident


---

### Datasets


- [Seattle WA Collisions 2004-2019](./Collisions.csv)
from https://data-seattlecitygis.opendata.arcgis.com/datasets/collisions/data?geometry=-122.825%2C47.452%2C-120.848%2C47.776&where=PEDCYLCOUNT%20%3E%3D%201

---

### Data Dictionary

Link contains a description of the column names a the type of data they contain.
[data description](https://www.seattle.gov/Documents/Departments/SDOT/GIS/Collisions_OD.pdf).
One-Hot Encode columns were added for some catagorical variables.

---
### Executive Summary

Collision data was filtered to incidents that included a bicycle. The classes were very imbalanced with the majority class being Injury at 4510, Property Damage at 635, Serious Injury 438, and Fatality at 25. The classes were rebalance with oversampling of the minority classes. Otherwise the model would just predict the majority class for every incident. Several models were tried Random Forrest performed the best. Grid Search was used to find hyperparameters.



### Conclusions:

With the imbalanced classes the null model had an accuracy of 0.81 by just predicting the majority class. The Random Forrest model on had an accuracy of 0.76 and was only doing that well by just predicting the majority class most of the time. When looking at the confusion matrix it did not predict any of the other classes well. The incidents were mostly related to the amount of bikes on the road. More accidents in summer and in the afternoon during rush hour. The wasn't a relationship between the features in the data set and the types of incidents. More data needs to be combined into the data set with other possible features like speed limits, bike lanes, and traffic cameras. This may produce better results.  
