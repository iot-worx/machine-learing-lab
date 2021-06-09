# Machine Learning Lab

This repository contains source code for a Machine Learning (ML) workshop using Amazon SageMaker. 
1. Binary classification problem using the [Titanic survivor dataset](https://www.kaggle.com/hesh97/titanicdataset-traincsv)
2. Time series forecasting using the [NASA Turbofan Degradation dataset](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/) 


## Steps

Follow the steps outlined in the `README.md` file under each exercise directory.


## Contents

* `1_classification`
  * `datasets/`
    * `titanic.csv`: Titanic survivor dataset.
  * `1_exploring.ipynb`: Exploration of the Titanic dataset.
  * `2_cleaning.ipynb`: Cleaning of the Titanic dataset.
  * `3_processing.ipynb`: Preprocessing of the Titanic dataset.
  * `4_training.ipynb`: Training the logistic regression model using the Titanic dataset.
  * `README.md`: Contains instructions for the workshop.
* `2_predictive-maintenance/`
  * `entry_point/`
    * `script.py`: Entry point script containing MXNet implementation for training the model.
  * `1_fetch.ipynb`: Fetch the Nasa Turbofan Degradation dataset.
  * `2_cleaning.ipynb`: Cleaning and exploration of the dataset.
  * `3_processing.ipynb`: Processing the dataset for model training.
  * `4_training.ipynb`: Training and inference with the model.
  * `README.md`: Contains instructions for the workshop.


## License

[MIT](https://choosealicense.com/licenses/mit/)


dsandhjkasndkjsah