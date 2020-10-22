## Spam Detection using machine learning approaches ##

The project goal is to build predictive model which can be used to identify spam email. Also, infer the relationship between the predictors and the response. The URL of the dataset is [here](https://www.kaggle.com/balaka18/email-spam-classification-dataset-csv). The scope of the project is to apply concepts learnt in class on the dataset. R language has been used throughout the project. .R and .Rtml has been uploaded in the code folder.

Initially, there were 3000 predictors in the dataset. I ran out of memory due to large number of predictors. Then I tried feature selection techniques to work with the most significant features for the rest of the project. Finally, there are 30 predictors in the dataset which are which are the most common words in all the emails. The predictor values are all real numbers. There are 5172 instances, each instance for each email. For each instance, the count of each predictor (column) in that email (instance) is stored in the respective cells. The information regarding all the emails are stored in a data frame for analysis. 

The final dataset, email_v2.csv, used for analysis is also uploaded in the data folder.

Detailed comments and interpretation are included in the code.

The project is published [here](https://rpubs.com/redwanwalid/spam-detection).
