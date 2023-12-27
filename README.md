# Kidney-Disease-Classification-MLflow-DVC

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Jubbu05/Kidney-Disease-Classification-Deep-Learning-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n myenv python=3.8 -y
```

```bash
conda activate myenv
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt

```

### DagsHub
[DagsHub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/Jubbu05/Kidney-Disease-Classification-Deep-Learning-Project.mlflow \
MLFLOW_TRACKING_USERNAME=Jubbu05 \
MLFLOW_TRACKING_PASSWORD=eb824e39600fb3ccc66feefb3688f10eafd33e8b \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/Jubbu05/Kidney-Disease-Classification-Deep-Learning-Project.mlflow

export MLFLOW_TRACKING_USERNAME=Jubbu05

export MLFLOW_TRACKING_PASSWORD=eb824e39600fb3ccc66feefb3688f10eafd33e8b

```