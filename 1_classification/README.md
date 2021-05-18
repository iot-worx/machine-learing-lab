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


## Run the Jupyter Notebooks

1. In the Notebook instance page click on `Open JupyterLab` next to the instance you just created.
1. Navigate to the `/1_classification/` directory.
2. Double click on the desired `.ipynb` file to run the notebook.
1. When prompted to select a Kernel choose `conda_python3`.
1. Each cell can be run by clicking the ‘Run’ button on the toolbar at the top.
