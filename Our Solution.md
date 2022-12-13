[[MLOps]]

![[MLOps-Solution.png]]

### - Currently we have deployed [[MLFlow]] for Artifact Storage (models) and Experiment Tracking (Hyperparameters). MLFlow is backed by [[Minio]] for Model storage and [[Postgresql]] for Hyperparameter storage. 

### - We use Jupyter Notebooks for [[Experimental Programming]] and GitHub for version control.

### - The cluster is effectively a distributed development environment. It is used in conjustion with the existing CI/CD pipelin.

	 - We deploy from Github to the staging and production environments using Jenkins.
	 - Models are served using Tensorflow Serving from the Docker Swarm.

### - There are other tools we are looking to install but next steps are to deploy an Ingress Contoller to lock down the cluster.

## Links

- [Example MLFlow Notebook](https://github.hpe.com/TS-RnD/mlaas/blob/master/training/PI_models_proliant-with-mlflow.ipynb)

- [MLFlow](http://manager.k8s.tssrd.hpecorp.net:30500/#/experiments/2)

