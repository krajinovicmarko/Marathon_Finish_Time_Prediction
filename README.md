## About The Project

The objective of this project is to create a machine learning model in Python for predicting marathon finish times based on age, gender, and 5 km, 10 km, or 21.1 km (Half marathon time) race time running at a marathon pace.
The model is designed for runners who are already capable of completing a full marathon, as it will be trained on data from runners who have successfully finished the entire marathon distance.
This predictive tool can be valuable for individuals preparing for a marathon, providing an estimate of their potential marathon finish time.
This is particularly useful since many marathoners typically do not run more than 32-35 km during their training for a marathon. 

The project is divided into two parts:
1) The first part will explore data used for predicting marathon finish time. Exploratory Data Analysis (EDA) is shown in jupyter notebook [EDA_marathon_jyupiter](https://github.com/krajinovicmarko/Marathon_Finish_Time_Prediction/blob/main/EDA_marathon_jyupiter.ipynb)
2) The second part will show the development of 3 machine-learning regression models with the following features:
     * Age, Gender, and 5 km race time [5K_Model_Training_Marathon](https://github.com/krajinovicmarko/Marathon_Finish_Time_Prediction/blob/main/5K_Model_Training_Marathon.ipynb)
     * Age, Gender, and 10 km race time [10K_Model_Training_Marathon](https://github.com/krajinovicmarko/Marathon_Finish_Time_Prediction/blob/main/10K_Model_Training_Marathon.ipynb)
     * Age, Gender, and Half marathon race time [21K_Model_Training_Marathon](https://github.com/krajinovicmarko/Marathon_Finish_Time_Prediction/blob/main/21K_Model_Training_Marathon.ipynb)

We can observe the R2 values within the range of 0.77-0.90, and MAE falls between 516-882 seconds, 
which is really good given that we are attempting to predict marathon finish time based on age, gender, 5 km, 10 km, or half marathon race time.

## Contact

Marko Krajinović - [LinkedIn profile](https://www.linkedin.com/in/marko-krajinovi%C4%87-6959a320a/) - marko.krajinovic1994@gmail.com

Project Link: [Marathon_Finish_Time_Prediction](https://github.com/krajinovicmarko/Marathon_Finish_Time_Prediction/tree/main)


## Acknowledgments

Dataset can be accessed via this link [Finishers Boston Marathon 2015, 2016 & 2017](https://www.kaggle.com/datasets/rojour/boston-results)

