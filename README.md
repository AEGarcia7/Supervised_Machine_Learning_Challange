# Supervised Machine Learning Challange

## **Description:** 
Using both logisitical regression and random forest classifier, figure out which out of the two works better in modeling and predicting the dataset.

# Data Used:

lending_data.csv

# Made by:
Alfredo Garcia

# Technologies:
Scikit-learn, Numpy, Pandas


# Analysis
[![Supervised01.png](https://i.postimg.cc/9MdjtfFF/Supervised01.png)](https://postimg.cc/XGYhn4CT)
1. After reading the data, I took the loan status and put it as the Y axis. The rest of the table was made into the X axis. Then all the info was made into the test and train x/y axis.

[![Supervised02.png](https://i.postimg.cc/J0RCTWG3/Supervised02.png)](https://postimg.cc/r0ZHm3Gz)

2. For the linear regression, all that needed to be done was load the model, and fit the data into it to train it. 

[![Supervised03.png](https://i.postimg.cc/MHt2NrQC/Supervised03.png)](https://postimg.cc/rRdPtjgj)

3. For the random forest classifier, first the X axis needed to be scaled so the scaler was loaded, the data was inserted, and then the results were renamed for later usage.
For the actual modeling, all that needed to happen was plug the train for both the Y axis and the scaled X axis and get the results.

4. The results of the modeling is that the training of the random forest classifier had a better training score by around .006 but the linear regression had a better test score by around .0006 so in the end the linear regression has better prediction.