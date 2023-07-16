# Product-Length-Prediction📦📦
* Using the given dataset, train & test , downloading as csv file and loading them into google colab.

* Importing   numpy ,pandas, seaborn and matplotlib for the functionalities to be used in the notebook.

* Then cleaning the data by doing some operations such as finding the shape, info, etc

* Then by using isnull() finding the null values whether they exists.

* Null values exists for BULLET_POINTS, DESCRIPTION & TITLE columns.

* Dropping out the columns which has more null values.
  
* Finding the duplicate values whether they exists.
  
* Duplicate values doesn’t exists.
  
* Finding the skewness and the skewness exists more for PRODUCT_LENGTH.
  
* Using the interquantile function the skewness of the PRODUCT_LENGTH is reduced.
  
* Then plotting the PRODUCT_ID,PRODUCT_TYPE_ID &PRODUCT_LENGTH.
  
* Since the variation exists for PRODUCT_LENGTH dropping the PRODUCT_LENGTH column.

* Then storing the PRODUCT_LENGTH in y_test.

* Then splitting the dataset as X_train and y_test by importing the sklearn function.

* Then predicting the PRODUCT_LENGHTH which is stored in y_test using SVR Algorithm.

* Since the prediction result is in the form of array , converting them into dataframe and the result is predicted.

* Then concating the PRODUCT_LENGTH  & PRODUCT_ID by using the concat function.
Both the columns got concatenated and the result is obtained as per the sample submission file.
