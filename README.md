# first_ml_project
My first ML project using python, MLFlow, Panda, SCLearn, Jupyter notebooks, docker, kubernates and VSCode
### Section 1
- Basic experiment training, evaluating and tracking with MLFlow.
- Files are stored in src folder.
### This is a Basic experimental tracking program using MLFlow.

### Section 1 - Application testing in your local lab venv 
1. `train.py` is the main program used to generate data, split and test it. Logging has also been incorporated into it.
2. `requirements.txt` has dependencies needed to run python application which are numpy, pandas and scikit-learn.
3. `Dockerfile` to package application to run within a docker containiner with a python base image.
4. To create a python environment to test the application in, run the commands below.
- `python -m venv mlflowapp`
- `source mlflowapp/bin/activate`
- `pip install mlflow` Install MLFlow within the python environment
- `python train.py` This will generate logs to mlflow.log
- `mlflow ui`
5. Open MLFlow in your browser at http://localhost:5000
6. Go to model training tab and view stats about your trained and tested dataset
### Section 2 - End to end pipeline or ML Model
- In this section, we are going to build an end-to-end pipeline to create a model.
- This will include Data Dreprocessing, Model Training, Model Evaluation and final save and load model.
- Will be using Jupter Notebooks for this task and storing it within the notebooks folder.
#### Creating a python Virtual Environment
- Creating a virtual environment. `python -m venv pathToProd`
- Activate the newly created environment `source pathToProd/bin/activate`
- Install Jupyter Notebook `pip install notebook`
- Run this command to start jupyter notebook`jupyter notebook`

### Section 3
