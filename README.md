# Garment-Worker-Productivity-Prediction-Project

Title: Garment Worker Productivity Prediction Project 

Project Description: This project is to predict the productivity of garment worker with regression analysis with using garment worker productivity dataset that can be found in https://www.kaggle.com/ishadss/productivity-prediction-of-garment-employees. 

Details: The first step of the project is by importing relevant packages. Then, the path file of the dataset is provided to upload the dataset into the code. The contents of the dataset is 1197 rows x 15 columns. The label is actual_productivity but the features need to be clean up as some column is not necessary to be used for training and testing the model later. The data visualization was done to visualize the relationship between colum and most importantly was pearson correlation since it is useful to determine the relationship between column. The feature was engineered with feature syntheisis with np.log, mean, media,n, label encoding, etc. The feature synthesis is to transform several columns into better features by applying mathematical functions and creating new columns or features to automate machine learning process. After feature engineered, the basic model developed with applying L2 regularizer in dense layer. Finally, the model was running and the loss and mean absolute error visualized.
