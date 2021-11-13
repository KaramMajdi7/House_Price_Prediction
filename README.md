# House_Price_Prediction

This project was created using Machine Learning with Python, the project was made by using the
Boston house price prediction dataset, which is a dataset that comes from UCL machine learning
repository, and this data was collected in 1978, the data has 506 entries that represents aggregate
information about 14 features of homes located in boston.

In this particular project I used XGBoost Regression, and it's regression beacuse
it's about predicting a quantity, and firstly in the project I imported several 
libraries such as pandas, matplotlib, sklearn, numpy and seaborn, then I loaded the
boston dataset using the sklearn datasets, then I created a dataframe using pandas 
then I included the target which is the price value of this dataframe, and the I printed the
shape of the dataframe which is (506, 14), the I checked if there was any missing 
values in the data, and then I checked the statistical measures which was the mean value and 
others, then I checked for the correlation between the various features in the dataframe 
using a heatmap, and then splitted the dataset into data and label, and then splitted
the data into training and test data with the help of the train test split function,
and I stated the test size to 20 percent, and then trained the XGBoost regression
model usnig the XGBRegressor function, and the train the model with fit function
with the train data, I have evaluted the data for both training and test data, and I
checked the error values which was quite good, and at last pltted the actual price
and the predicted price in a graph using the matplotlib library, and the results were very 
close to each other.

![graph](https://user-images.githubusercontent.com/74671857/140745563-16e8d9d4-72c2-4576-ad58-d0f49a0806ca.JPG)
