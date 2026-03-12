# first_ml_project
My first ML project using python, MLFlow, Panda, SCLearn, Jupyter notebooks, docker, kubernates and VSCode
### Section 1
- Basic experiment training, evaluating and tracking with MLFlow.
- Files are stored in src folder.
### This is a Basic experimental tracking program using MLFlow.

### Application testing in your local lab venv 
1. Create `train.py` with program to use libraries to generate data, split and test it.
2. Create `requirements.txt` with dependencies needed to run python application
3. Create `Dockerfile` to package application to run within a docker containiner.
4. Create a python environment to test the application in.
- `python -m venv mlflowapp`
- `source mlflowapp/bin/activate`
- `pip install mlflow` Install MLFlow within the python environment
- `python train.py` This will generate logs to mlflow.log
- `mlflow ui`
5. Open MLFlow in your browser at http://localhost:5000
6. Go to model training tab and view stats about your trained and tested dataset
### Section 2

### Section 3
