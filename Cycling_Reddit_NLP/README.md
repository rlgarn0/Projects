# NLP: Reddit web scraping 

### Problem Statement

Can a model classify mountain biking and road cycling post?
Is it better than guessing the majority class?

---

### Datasets

Dataset scraped from Reddit:

- [Reddit bikes dataframe](./datasets/bike.csv)
- [Reddit Velo dataframe](./datasets/velo.csv)
- [Reddit MTB dataframe](./datasets/MTB.csv)
---

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
text|object|bike|Text from reddit posts
roadie|int64|bike|'1' come from Velo subreddit and '0' come from MTB subreddit

---
### Executive Summary

As technology moves into every sector of the economy it has an effect on the cycling industry as well. A number of Apps have been created for training and navigation. This in addition to the traditional market of bikes and accessories. Road cyclist and Mountain biker demand different products, but they are still on bikes. Have a way to target different cyclist based on their specific type of riding is import to put the right products in-front of them. A model could be use do predict the type of cyclist a person is based on posts.


### Conclusions:

Using a logistic regression model posts were able to classified as mountain biking or road cycling at a 89% accuracy rate. The null prediction would be 51% by guessing the majority class. The model does very well at predicting classes for the level of seriousness necessary, meaning a misclassification doesn’t cause much harm. 