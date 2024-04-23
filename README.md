# Chapter 10: Classification

## Data-Driven Categorization of Objects in Tourism
## http://www.datascience-in-tourism.com/

***[Ulrich Bodenhofer](https://github.com/Ubod)*** & ***[Andreas Stöckl](https://github.com/astoeckl)***

### Abstract

Classification, the task of assigning objects to a given set of categories, is used in almost every field. One important sub-branch of classification consists of methods that learn classification functions from example data. The following chapter will provide an overview of the most basic concepts and methods of this type of data-driven classification. This repository provides a Jupyter notebook along with a data set from a tourism-related use case that exemplifies how to classify visitors of a hotel website into bookers and non-bookers based on their interests and their behavior and actions on the website. The notebook applies various classification methods and evaluates the results.

### Environment Setup

The notebook was created using `Python 3.8.10`. You need the following packages: `pandas`, `numpy`, `sklearn`, `plotly`, `matplotlib`, and `xgboost`. Additionally, you need a properly configured IPython kernel.

If you are using [Anaconda](https://www.anaconda.com/), we recommend performing the following steps upon cloning the repository (replace environment name `DSIT` as you like):
```bash
## create a new Anaconda environment and activate it
conda create -n DSIT
conda activate DSIT

## install packages
conda install -n DSIT ipykernel jupyter pandas numpy plotly sklearn matplotlib xgboost

## build IPython kernel
python -m ipykernel install --user --name DSIT --display-name "Python (Data Science in Tourism)"

## now you can start a Jupyter session
jupyter notebook
```

On a Windows system with Python 3 without [Anaconda](https://www.anaconda.com/), we recommend performing the following steps upon cloning the repository:
```bash
## create a new Python environment and activate it
python -m venv .env
.env\Scripts\activate

## install packages
pip install ipykernel jupyter pandas numpy plotly sklearn matplotlib xgboost

## build IPython kernel
python -m ipykernel install --user --name .env --display-name "Python (Data Science in Tourism)"

## now you can start a Jupyter session
jupyter notebook
```

On a Linux/Mac OS system with Python 3 without [Anaconda](https://www.anaconda.com/), we recommend performing the following steps upon cloning the repository:
```bash
## create a new Python environment and activate it
python3 -m venv .env
source .env/bin/activate

## install packages
pip install ipykernel jupyter pandas numpy plotly sklearn matplotlib xgboost

## build IPython kernel
python -m ipykernel install --user --name .env --display-name "Python (Data Science in Tourism)"

## now you can start a Jupyter session
jupyter notebook
```

### Contact

Ulrich Bodenhofer - [Homepage](http://ulrich.bodenhofer.com) - [LinkedIn](https://www.linkedin.com/in/ulrichbodenhofer/)

Andreas Stöckl - [Homepage](http://www.stoeckl.ai/) - [LinkedIn](https://www.linkedin.com/in/andreas-st%C3%B6ckl-57682113a/) - [Twitter](https://twitter.com/stoecklai)
