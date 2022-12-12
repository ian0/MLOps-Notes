[[MLOps]]

Keep track of important information about your experiments such as parameters, metrics and models.

Options:

[ClearML]([https://github.com/allegroai/clearml](https://github.com/allegroai/clearml)), [MLFlow](https://github.com/mlflow/mlflow), [Determined]([https://github.com/allegroai/clearml](https://github.com/allegroai/clearml)), [DVC](https://github.com/iterative/dvc), [Tensorboard]([https://github.com/tensorflow/tensorboard](https://github.com/tensorflow/tensorboard))

## MLFlow

MLflow is an open source platform to manage the ML lifecycle, including experimentation, reproducibility,              
deployment, and a central model registry. MLflow currently offers four components:

-   MLflow Tracking: Record and query experiments: code, data, config, and results
-   MLflow Projects: Package data science code in a format to reproduce runs on any platform
-   MLflow Models: Deploy machine learning models in diverse serving environments
-   Model Registry: Store, annotate, discover, and manage models in a central repository

[MLflow Tracking Server enabled with proxied artifact storage access](https://mlflow.org/docs/latest/tracking.html#id32)[](https://mlflow.org/docs/latest/tracking.html#scenario-5-mlflow-tracking-server-enabled-with-proxied-artifact-storage-access "Permalink to this headline")


![[mlflow-proxied.png]]


[[Minio]]

[[Postgresql]]