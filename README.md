Predicting Rainy days in Australia 
==============================

Description
------------  
The following project aims at analysing the weather data in Australia from 2009 to 2017. We want to predict the incidence of rainy days. The dataset used contains 10 years of daily weather data from several locations across Australia. We use Machine Learning Models as well as Deep Learning Models to make our predictions.

Results
------------  
The results can be all found in the modelling report in the reports folder. Our Machine Learning Models did a better job in predicting rainy days. 

Running the project
------------
If you want to compute yourself our results you have to run the corresponding jupyter notebooks in the folder notebooks. 

Data Source
------------  
Rain in Australia: Weather in Australia, dataset for 10 years from 2007 to 2017 from numerous Australian weather stations.

The data is freely available at Kaggle under the following link: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

Project Organization
------------         
    ├── data               
    │   ├── map            contains all files necessary to use the map of Australia
    │   ├── processed      contains the pre-processed data set: weatherAUS_imputed.csv, and result of different ml models: mlm compare.csv
    │   └── raw            contains the raw data set: weatherAUS.csv
    │
    ├── notebooks         
    │   ├── DeepModels      contails all the Neural Network models: NeuralNetworkModelling.ipynb, NeuralNetworkModelling_stable.ipynb
    │   ├── MLModels        contains all the Machine Learning Model notebooks, alongwith interpretation and mlm comparison notebooks
    │   └── Preprocessing   cotains the notebook for preprocessing the raw data: PreprocessingFinal.ipynb
    │                         
    ├── reports            Preprocessing_Report                          
    │                      Modelling_Report 
    |                      Merged: Final reprt
    ├── .gitignore
    ├── LICENSE
    ├── README.md 
    └──requirements.txt   
    
Note: For the notebooks we used joblib to store certain model information and avoid recomputing model results which took a lot of time to run. The joblib files are too big to be stored on github however.

