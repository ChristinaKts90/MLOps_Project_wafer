# MLOps_Project_wafer

In this project we will see step by step how we can create a fully automated pipeline

## Setting up the environment
### Setting up the Github repository
1.  Create a new repository for the project in your github and add it to your desktop
2.  In a current conda environment 
```
pip install cookiecutter # Install cookiecutter
cookiecutter -c v1 https://github.com/drivendata/cookiecutter-data-science
```
3.  Create the environment for your project
```
conda create -p venv python=3.9 -y 
conda activate F:\Github\MLOps_Project_wafer\venv
```
4.  git commit -m "first commit"
5.  git branch -M main
6.  git remote add origin https://github.com/Christinakatsiafa/MLOps_Project_wafer.git
7.  git push -u origin main

### Setting up the conda environment
Now empty the requirements.txt so we can create our own
```
# external requirements
cookiecutter
dvc
# local package
#-e .
```
To run the requirements.txt
```
pip install -r MLOps_Project_wafer\requirements.txt
```
## Create and checkout a development branch
```
git checkout -b dev
```
