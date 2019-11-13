Question 1(Classification)
(i)Read the classification datasets (training and testsets) into a NumPy array. This is a binary classification problem. As usual the last column is the class label (0 or 1). All other columns are numerical features. (ii)Using Scikit Learnbuild a basic kNN classifiermodel for this dataset (start with k=1) and assess itsclassification accuracy.(iii)Explore the impact of adopting various values of k on your modeland different distance metrics. (iv)Next contrast the performance of the kNN model with other classification models. For example, try the following:a.DecisionTreeClassifierb.Naïve Bayesc.SVM

Question 2(Regression)(i)In the exercise folder you will find a file called regressionExample.csv. Read this file into a NumPy array (ii)Use train_test_splitto split the dataset into 20% test and 80% training. (iii)Use a KNeighborsRegressorto build a predictive model for the data and assess its accuracy using R2. 

Question 3 (Outlier Detection)(i)In the exercise folder you will find a zip file called outlierData.zip. This zip file contains a training file and test csv file. This is a regression problem and target value is contained in the last column in each file. Read this data into your program. (ii)Build a model using DecisionTreeRegressorand assess the accuracy (using R2). (iii)Identify any outliers in the training data using boxplots.(iv)Remove the outliers and reassess the new accuracyof the model. For the purposes ofthis exercise you can just focus on removing datapoints that are significantly distant from the upper and lower whiskers of the boxplot.(v)Try an alternative model such as a KNeighborsRegressorand record the accuracy. 