This "Image Classification with Sagemaker" Jupyter notebook is a tool for building image classification machine learning model using our own image data. It uses Amazon S3 to store data and AWS SageMaker for training and inference.

You can upload your images data, grouped by categories (e.g. car, plane, etc). Each category should be uploaded in its own folder. The tool will shuffle and split the data for training and validation, generate list file, and upload the data to S3. The tool will then initiate a training job in SageMaker. The inference code is also provided.

In order to run this, open SageMaker service in your AWS UI console. Create a Notebook Instance and open it. Download/clone this tool and run it step by step according to the instructions in the jupyter notebook file.