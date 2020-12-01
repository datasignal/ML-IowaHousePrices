# ML - Iowa House Prices

In this project, we will try to predict the prices of the houses in Ames (Iowa US) by using only linear regression models with and without regularization (Ridge and Lasso). We will start by loading and cleaning the data, then gain insights with a strong exploratory data analysis and finally build different linear regression models :

1. A baseline model
2. A simple model with only two variables
3. An intermediate model with 20 variables
4. A model using all the variables provided in the dataset

We will compare these models by using a training and test set and discuss the results.

The following packages are required to execute the notebook :
* `python`
* `numpy`
* `pandas`
* `scipy`
* `scikit-learn`
* `matplotlib`
* `seaborn`

If using `conda`, a ready to use environment can be created with the commands :
```bash
# Create the conda environment
> conda create -f environment.yml

# Activate the environment
> conda activate ml-iowahouseprices

# Launch Jupyter notebook server
> jupyter notebook
```