# genetic-algorithm-trip-optimizer
The project splits in 2 parts. In first part initially we use data analysis and feature extraction for dataset. After that we define the best model that can use extracted features to predict the travel time with least possible error. In the second part we use genetic algorithm to find the path between random locations in test data which has the minimum distance. 


## Dataset
The dataset is available online
You can find it here: https://www.kaggle.com/c/nyc-taxi-trip-duration/data

### NYC_Taxis_Data_Analysis_Cleansing.ipynb

In the first step we analize the data, detect inconsistecy and get rid of problems.

### XGBoost_Model_For_NYC_TaxiDB.ipynb

Next, We build the model based on the output file of the previous step.

### TSP_Genetic_Optimizer.ipynb

In this step we build the genetic algorithm optimizer based on the previous step output model.


**TODO NEXT:**

Use PSO algorithm for solving TSP problem

**TODO NEXT**

Use differnet customized kernels for SVM Regression and use it for building model.
