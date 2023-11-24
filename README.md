# template_ml
Provide a template project for ML with python, poetry and make

## Petry 

First, initialize the project with poetry init.

```bash
poetry init
```

Then use petry shell to create a virtual environment and install the dependencies for development. 
For Pycharm users, you can use the virtual environment created by poetry as the project interpreter.

```bash
poetry shell
poetry add numpy panda matplotlib scikit-learn jupyterlab pre-commit  -G dev
```

## Folder structure

Create a folder for notebooks and a folder for data. Also create a folder for scripts and temp data.
The temp and data folders will also be added to .gitignore.
```bash
mkdir notebooks
mkdir data
mkdir scripts
mkdir temp
```



