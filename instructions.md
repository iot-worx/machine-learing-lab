# ML Predictive Maintenance Workshop Steps

## Background

Companies need to monitor their industrial assets to ensure sustained performance and the typical manual routine checkups are time-consuming and reactive. However, with the advent of cheap sensors, companies can get metrics from industrial assets at regular intervals and with this trove of data, companies can use machine learning models to predict when assets might fail.


This project shows how to use Amazon SageMaker to train a deep learning model that uses historical sensor readings to predict how much longer the asset is likely to work for before it becomes critical. As a demonstration, the project trains an MXNet model on the NASA turbofan engine dataset, but can be easily customized to work with other sensor based data.


## Steps

### Create an S3 bucket to store data and built models

1. Visit the [AWS S3 console page](https://console.aws.amazon.com/s3) and click the `Create Bucket` button.
1. Fill in a Bucket Name for your S3 bucket.
1. Click the `Create Bucket Button`.
1. Take note of your chosen S3 bucket name.


### Create an AWS SageMaker Notebook instance

1. Visit the [AWS SageMaker console page](https://console.aws.amazon.com/sagemaker).
1. Choose `Notebooks` -> `Notebook instances` in the left hand pane.
1. Click the `Create notebook instance` button.
1. Fill in the `Notebook instance name` field.
1. In the Permissions and encryption section click the `IAM role` dropdown and select `Create a new role`.
1. Choose the `Specific S3 buckets` option and fill in the S3 bucket name from above and click `Create role`.
1. In the `Git repositories` section, click on the `Repository` dropdown and select `Clone a public Git repository to this notebook instance only`.
1. In the `Git repository URL` field add: "https://github.com/iot-worx/predictive-maintenance-workshop.git".
1. Click on `Create notebook instance`.


### Run the Jupyter Notebook

1. Click on `Open Jupyter`.
1. Click on the `predictive_maintenance_workshop.ipynb` file to open the jupyter notebook.
1. When prompted to select a Kernel choose `conda_python3`.
1. On the last line in the first cell, paste your bucket name inside the quote characters.
1. Each cell can be run by clicking the ‘Run’ button on the toolbar at the top.