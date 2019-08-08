# citibank_defaulter
DSE Projects

This is the main file which contains the entire code.

Firstly, merged all 3 training files into 1.
Then performed a basic eda of descriptive statistics and univariate graphs of each variable using pandas profiling.
Then created a couple of bivariate graphs with respect to target variable i.e. wheather the person is defaulter or not
Plotted a heatmap to check for corealtion between variables.
Scaled the Data using StandardScalar: Bringing the data into a similar scale.
Applied a simple RandomForest Model without any hyperparameter tuning
Then using Grid Search Cross-Validation found out the best parameters to tune the model
Finally, applied the Tuned model to get the predicted values for the tes file.
Lastly, submitted the predicted values to Kaggle.
Result: Test results for Tuned RF generated an accuracy of ~81.7%

Software Configuraion: Python - 3.7.3 Jupyter Notebook - 5.7.8
