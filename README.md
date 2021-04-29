# Machine Learning Lab

This repository contains source code for a Machine Learning (ML) workshop using Amazon SageMaker. It is broken into two parts:
* 1: Binary classification problem using the [Titanic survivor dataset](https://www.kaggle.com/hesh97/titanicdataset-traincsv)
* 2: Regression problem of time-series data to build a predictive maintenance model using the [Nasa turbofan engine dataset](https://data.nasa.gov/dataset/Turbofan-engine-degradation-simulation-data-set/vrks-gjie)


## Steps

Follow the steps outlined in the `instructions.md` file under each directory to complete the lab.


## Contents

* `1_classification`
  * `datasets/`
    * `titanic_train_csv`: Titanic survivor dataset.
  * `titanic_exploration.ipynb`: Exploration and preparation of the Titanic dataset.
  * `titanic_logistic_regression.ipynb`: Trains the binary classifier model.
  * `instructions.md`: Contains instructions for the workshop.
* `2_regression/`
  * `entry_point/`
    * `script.py`: Entry point script containing MXNet implementation for training the model.
  * `data_exploration.ipynb`: Exploration of the turbofan data set.
  * `predictive_maintenance_workshop.ipynb`: Trains and deploys the predictive maintenance model for batch transformation.
  * `instructions.md`: Contains instructions for the workshop.


## License

[MIT](https://choosealicense.com/licenses/mit/)