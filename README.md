# Everlytics-Internship-Test

My approach in solving this Machine Learning problem.
1. When I examined the dataset, I understood that I have to predict if the website is Phishy [1] or not [0].
2. This is a Binary Classification problem. So I had to use Supervised classification algorithms (as the output was already given).
3. I skipped EDA as the features were in the form of 0 and 1, -1 and 1. 
4. The data was already cleaned so no need of feature extraction.
5. I divided the dataset into input data (independant features) [X] and output data (dependant features) [Y] for splitting the dataset into training set and test set. This step was taken to gauge the accuracy of my model on training data and test data (new input). 
6. The next step I performed was of feature selection. I first trained my Logistic Regression model on the complete data. It gave 92 % accuracy. Then I trained my model on selected features which had high correlation on dependant feature [Y] (Result). The accuracy got improved to 95 %. So I went with the selected features.
7. In feature selection, I first tried Lasso Regression and compared it with Ridge Regression. The output accuracy of my model on features selected by Lasso Regression was significantly higher as compared to values predicted with the help of Ridge regression. So I went with Lasso Regression.
8. After selecting the features, I started fitting and testing my Classification models on the data. These were my test results.
   I got 95 % accuracy from Logistic Regression model on test data.
   I got 97 % accuracy from RandomForest Classifier model on test data.
   I got 98 % accuracy from Decision Tree Classifier model on test data.
