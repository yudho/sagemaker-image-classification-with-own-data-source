This Jupyter notebook is a framework for building image classification machine learning model using our own image data. 
It uses Amazon S3 to store data and AWS SageMaker for training and inference.

You can upload your images data, grouped by categories (e.g. car, plane, etc). Each category should be uploaded in its own folder. The tool will shuffle and split the data for training and validation, generate list file, and upload the data to S3. The tool will then initiate a training jobs with hyperparameter tuning in SageMaker. The inference code is also provided.

In order to use this, follow these steps:

1. Open AWS UI Console at https://console.aws.amazon.com and open SageMaker service
2. Click"Notebook Instances" on the left menu, and create a new notebook
3. After created, open the Jupyter Notebook on the new notebook instance
4. Open the Jupyter Notebook terminal and git clone the code
5. Open the 'sagemaker-image-classification-with-own-data-source.ipynb' file and Run

