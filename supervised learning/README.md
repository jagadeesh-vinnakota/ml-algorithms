# Concepts need to know before diving and playing with code. 


### Any machine learning project follows below steps

        1. Data collection
        2. Data cleaning
        3. Data preprocessing
        4. Training a machine learning model
        5. Serve the machine learning model depends on the use case.


### 1. Data collection
    Most of the time we need to build data pipelines that gathers data from different sources into our analytics space. We can use apache airflow for automating these data pipelines.


### 2. Data Cleaning
    The data that we collect may no be in the best form. There may be null values, missing values. In this step of data cleaning, we need to take care of this. Use this as a refrence on performing some of the data cleaning tasks
    
https://realpython.com/python-data-cleaning-numpy-pandas/
    

### 3. Data preprocessing
    The data we get after data cleaning may not be ideal for training a machine learning model. Some times, we need to standardize or normalize the data. 
    
Data preprocessing: https://medium.com/sciforce/data-cleaning-and-preprocessing-for-beginners-25748ee00743

Data preprocessing: https://towardsdatascience.com/preprocessing-with-sklearn-a-complete-and-comprehensive-guide-670cb98fcfb9

Data encoding: https://towardsdatascience.com/all-about-categorical-variable-encoding-305f3361fd02
    

### 4. Training an ML model
    The data we got after data preprocessing can be fed into many available machine learning models. We can use sklearn, tensorflow and many python libraries for this.
    
k-fold cross validation: https://machinelearningmastery.com/k-fold-cross-validation/

Loss Function: https://towardsdatascience.com/common-loss-functions-in-machine-learning-46af0ffc4d23

Cost Function: https://towardsdatascience.com/machine-learning-fundamentals-via-linear-regression-41a5d11f5220

Regularzation: https://towardsdatascience.com/regularization-in-machine-learning-76441ddcf99a
    
    
### 5. Serving the ML model
    Depending on the end user requirement, we can serve the ML model to the end user. One of the way is to wrap it under a REST API.


