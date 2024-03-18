# Machine Learning for Smart Grid Utility Predictions

Respository containing code for predicting meter readings of uOttawa FSS Main building based on external environmental factors.

[Poster Document](Group_5_Poster.pdf)

## Setting up Virtual Environment

```
# create new virtual environment
python -m venv ml_env

# activate virtual environment

# for Windows Users
.\ml_env\Scripts\activate

# for MAC Users
source ./ml_env/bin/activate

```
## Installing requirements

`pip install -r requirements.txt`

## Setting up Jupyter Lab

```
# install jupyterlab
pip install jupyterlab

# install ipykernel package
pip install ipykernel


# register the virtual environment that we created earlier as a Jupyter Kernel. From inside the virtual environment (ml_env) run below
python -m ipykernel install --user --name=ml_env

# launch jupyter lab 
jupyter-lab
```
## Developer Notes

1. The `Notebook` folder contains .ipynb files with the preprocessing, ml pipeline etc.
2. To perform EDA create separate notebooks that reads files dumped from pipeline notebook, or make necessary changes accordingly.
3. All results and plots of EDA analysis can go into `Plots` folder.
4. Refrain from pushing changes to the main branch. Create your own branch and push your individual branches to the repo. If changes to be applied to main branch, raise a PR.