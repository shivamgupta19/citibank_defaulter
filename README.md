# citibank_defaulter
DSE Projects

This is the main file which contains the entire code.

firstly, did eda and modelling on individual dataset i.e. train 1 and train 2.
After the release of last dataset i.e. train 3, merged all 3 training files into 1.
Then performed a basic eda of descriptive statistics(includes null values, duplicate values,etc)
Then created a couple of univariate graphs 
Plotted a heatmap to check for corealtion between variables.
None of the variables are correlated.
Splited data in train and test using train_test_split
Scaled the Data using StandardScalar: Bringing the data into a similar scale.
Applied a Bagging, Adaboost, DecisionTree, Gradient Boost without tunning.
Then using Grid Search Cross-Validation found out the best parameters to tune the Gradient Boost model.
Used ensemble model that is voting classifer to get the aggregated results of all the pre-applied models
Finally, applied the Tuned model to get the predicted values for the test file.
Lastly, submitted the predicted values to Kaggle.
Result: Test results for Tuned  generated an accuracy of ~81.469%

Software Configuraion: Google Colab
