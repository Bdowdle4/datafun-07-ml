# datafun-07-ml
P7 Introduction to Machine Learning

In this project, you'll:

+ Build a model
+ Make predictions
+ Visualize the model 
+ Publish your insights

### .gitignore needs

```shell
.vscode/
.venv/
.ipynb_checkpoints/
```

## How to Install and Run the Project

### Clone Your Repo

```shell
git clone "paste_your_repo_URL_here"
```

### Create Project Virtual Environment

On Windows, create a project virtual environment in the .venv folder. 

```shell
py -m venv .venv
.venv\Scripts\Activate
pip list
py -m pip install --upgrade pip
deactivate
```

### Create files in root folder

```shell
# Example for managing project requirements
code .
ni "requirements.txt"
```

### Add all dependencies by installing packages seperately
```shell
#Example If you have a requirements.txt list each package in this file
py -m pip install -r requirements.txt
#Example If you don't
py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy
```

### Freeze Your Dependencies
This will keep the package at the version it was installed as
```shell
py -m pip freeze > requirements.txt
```

### Git add and commit 

```shell
git add .
git commit -m "initial commit"
git push origin main
```
### Start Jupyter

```shell
#Example VS Code - in your project folder
code .
ni "filename.ipynb" #the file extension must be exactly ".ipynb" to open in jupyter
#Example Native Terminal - in your project folder
cd filename ##keep doing this until you reach the correct folder
jupyter lab #this command will also open in VS Code
```