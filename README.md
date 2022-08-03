# PROJECT: Rock/Mine Detection - KNN Model Implementation

## About the Project
Sonar (sound navigation ranging) is a technique that uses sound propagation (usually underwater, as in submarine navigation) to navigate, communicate with or detect objects on or under the surface of the water, such as other vessels.
The main goal is to develop a KNN ML model capable of detecting the difference between a rock or a mine based on the response of the 60 separate sonar frequencies.
The approach will consist in running GridSearchCV to tune the hyperparameter 'k-neighbors', first with no pipeline implementation; and afterwards, implementing pipeline from sklearn library.

## About the dataset
The data set contains the response metrics for 60 separate sonar frequencies sent out against a known mine field (and known rocks). These frequencies are then labeled with the known object they were beaming the sound at (either a rock or a mine).

* Data Source:
https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks)
