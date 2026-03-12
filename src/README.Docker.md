### This is a Basic experimental tracking program using MLFlow.

### Testing you application in your local lab

First, build your image, e.g.: `docker build -t mlmodel .`.
Create a python environment to test the application in.
1. `python -m venv mlflowapp`
2. `source mlflowapp/bin/activate`
3. `pip install mlflow` Install MLFlow within the python environment
4. `python train.py` This will generate logs to mlflow.log
5. `mlflow ui`
Open MLFlow in your browser at http://localhost:5000
Go to model training tab and view stats about your trained and tested dataset
