# genetic-algorithm-trip-optimizer
The project results in an evolutionary algorithm based agent which finds the best path for a Sales Person Problem. The agent uses Xgboost model to predict the trip duration and use that as the fitness metric.


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
