# collaborative-training-auth-client

This repository provides notebooks to easily interact with the authentication API for the collaborative training project

## Getting started with jupyter-notebook

In an environment of your choice, install the required dependencies

```
pip install -r requirements.txt
```
and run the following command to see your environment in `jupyter-notebook`
```
python -m ipykernel install --user --name=auth
```
Now, you can launch the notebook of your choice with `jupyter-notebook <notebook_name>.ipynb`

## Available notebooks

- `owner_create_experiment.ipynb`: Notebook to use when you want to create a new experiment (whitelist) on the API.
- `owner_update_experiment.ipynb`: Notebook to use when you want to update an experiment previously created on the API (change coordinator endpoint and list  of whitelisted participants).