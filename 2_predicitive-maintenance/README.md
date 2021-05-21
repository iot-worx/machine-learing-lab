# ML Binary Classifier Workshop Steps

## Create an AWS SageMaker Notebook instance

1. Visit the [AWS SageMaker console page](https://console.aws.amazon.com/sagemaker).
1. Choose `Notebooks` -> `Notebook instances` in the left hand pane.
1. Click the `Create notebook instance` button.
1. Fill in the `Notebook instance name` field.
1. In the Permissions and encryption section click the `IAM role` dropdown and select a role that has the form `AmazonSageMaker-ExecutionRole-XXXXXX`.
1. If no such role already exisits then click `Create role` and create a new role.
1. In the `Git repositories` section, click on the `Repository` dropdown and select `Clone a public Git repository to this notebook instance only`.
1. In the `Git repository URL` field add: "https://github.com/iot-worx/machine-learning-lab.git".
1. Click on `Create notebook instance`.

## Create an S3 Bucket

1. Visit the [AWS S3 console page](https://console.aws.amazon.com/s3)
1. In the lift hand panel click on `Buckets`.
1. Click on the `Create bucket1 button.
1. Fill in the `Bucket name` field.
1. You can leave all other fields at the default values.
1. Click the create `Create bucket` button at the bottom of the page.


## Run the Jupyter Notebooks

1. Visit the [AWS SageMaker console page](https://console.aws.amazon.com/sagemaker).
1. Choose `Notebooks` -> `Notebook instances` in the left hand pane.
1. Click on `Open JupyterLab` next to the instance you created.
1. Navigate to the `/2_predictive-maintenance/` directory.
2. Double click on the desired `.ipynb` file to run the notebook, starting with the first notebook.
1. When prompted to select a Kernel choose `conda_python3`.
1. Each cell can be run by clicking the ‘Run’ button on the toolbar at the top.
