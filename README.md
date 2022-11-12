# Classifying-Breast-Cancer-Malignancy
[Biol 419/519] Classifying Breast Cancer Malignancy Based off Cell Type Attributes with Machine Learning

## Repo Information:
This repository contains:

1. The main Python Notebook used to run and develop code
2. The Final Report
3. Data File for the Code
4. Images Used in the Final Reports

## Project Information:
One of the largest threats that cancer poses is through its ability to metastasize. Cancer metastasis is the ability for cancer to spread to other parts of the body – where a benign classification indicates no spread, and malignant indicates cancer metastasis. Accurate pre-emptive prediction of malignancy could be highly beneficial to treatment plans.
By running different classification based machine learning algorithms, we wanted to test whether it was possible to accurately predict if a breast cancer sample was benign or malignant, based on the different cell indicators. We’d also run linear regression models to see if there are any strong correlations between certain indicators and tumor classification. We also want to test whether mitosis rates correlates to malignancy.
We will be looking at breast cancer data, taken from Kaggle. The dataset was collected by Dr. William H. Wolberg, at the university of Wisconsin, Madison. The dataset comprises of 699 samples that Dr. Wolberg received for his clinical cases. In the dataset, each breast cancer sample has 10 attributes that describe the attributes of the cells, such as cell size uniformity and division rates for mitoses. Each sample also has an associated column with whether the sample was benign or malignant. The raw data was downloaded from https://www.kaggle.com/roustekbio/breast-cancer-csv.
For the classification, we would use Machine Learning, and cross-validate our data to test the predictive ability. To do so we would first parse the dataset into training and testing data. We would train the classifier with the training data exclusively, and then test its accuracy on the testing data. Since the testing data would be ‘new’ for the classifier, it could be used to see if cancer metastasis was predictable. For the data we were considering comparing a nearest-neighbor classifier, as well as a Linear Discriminant Analysis, adn SVM to see which performed better. We plan to use PCA for dimensionality reduction prior. To test whether mitoses rates correlate to malignancy we would use a least squares regression with our train data and then compare the accuracy of the regression against our test data.
In communicating the results we would need to find a way to quantify a classifiers predictive ability, so we could compare the machine learning technique and see which one is more accurate. We would do this by using the cross-validation, and testing for accuracy, by giving it test samples. From the cell attributes for the test samples, we would check whether the classifiers were able to correctly identify it as benign or malignant. To visual our data we would graph a scatter plot with our train-data with a decision boundary for malignant versus benign. On top of that we’d graph our test-data to visualize the accuracy of the model’s predictive ability.
