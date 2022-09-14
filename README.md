# Student_Acceptation_project
Building a model for predicting whether a student will be addmitted to college
In this project, we develop a model for predicting if a student will be admitted to college or not.
Dataset: https://www.kaggle.com/datasets/mahwiz/school-data
# Setup
Install dependecies
```
pipenv install --dev
```
Add Jupyter kernel :
```
pipenv run python -m ipykernel install --user --name="py39-student-acceptance-prediction"
```
Run Jupyter :
```
jupyter notebook
```
Use the py39-student-acceptance-prediction kernel
# Running it locally
Train a model :
```
pipenv run python train.py
```
Run Streamlit :
``` 
pipenv run stremlit run front.py
```
# Docker
Building it with Docker :
``` 
docker built -t student-acceptance-prediction:v01
```
Running it :
```
docker run it --rm \ -p 8501:8501 \ student-acceptance-prediction:v01
```
# Cloud 
The application id deployed to streamlit cloud :
https://alexeygrigorev-student-acceptance-project-front-bv02me.streamlitapp.com/

