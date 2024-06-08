# datafun-07-ml

## Create the project and clone to machine

#### I created a project repository on github and then cloned the repository to my machine.git 
```shell
git clone url
```

## Set up the environment
```shell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
py -m pip install jupyterlab numpy pandas pyarrow matplotlib seaborn scipy
py -m pip freeze > requirements.txt
```

### I added .venv and .ipynb_checkpoints/ to the .gitignore file.
### Open the jupyter notebook