# ONPProject

For this project, I used the OnlineNewsPopularity dataset that was donated to UCI's website in 2015. This dataset summarizes a heterogenous set of features about articles published by Mashable in a period of two years. The goal is to predict the number of shares in social networks (popularity).
I first had to preprocess the data : it included grouping some columns, deleting others or taking advantage of correlations to reduce the number of values.
Then I fitted different sklearn models with different parameters: LogisticRegression, RandomTreeClassifier, KNeighborsClassifier and SVC.
I ended up finding that RandomForestClassifier was the best model for this dataset with an accuracy of 51.22%. Unfortunately, the data is extremely heterogenous and I couldn't get a higher number.
