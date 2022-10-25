# ARIMA-and-Seasonal-ARIMA
Autoregressive integrated moving average (ARIMA) model and seasonal ARIMA model with milk production dataset

## [Notebook Here](https://github.com/SZun/ARIMA-and-Seasonal-ARIMA/blob/main/ARIMA-and-Seasonal-ARIMA.ipynb)

## Images from Notebook

![](./assets/original-data.png)
![](./assets/stats-data.png)
![](./assets/stats-data-2.png)
![](./assets/data.png)
![](./assets/autocorrelation-2.png)
![](./assets/autocorrelation-1.png)
![](./assets/forecast-1.png)
![](./assets/forecast-2.png)

## Getting Started

### Prerequisites

You must have anaconda and conda installed

```
$ anaconda --version
```
*# OUTPUT: "anaconda Command line client (version 1.11.0)"*
```
$ conda --verison
```
*# OUTPUT: "conda 22.9.0"*


### Installing

**Clone** the repo using SSH

```
$ git clone git@github.com:SZun/ARIMA-and-Seasonal-ARIMA
```

Then **cd** into the directory

```
$ cd ARIMA-and-Seasonal-ARIMA
```

Create the environment, add it to jupyter and launch jupyter lab

```
$ conda env create -f pytorch_env.yml
$ jupyter kernelspec remove ENVIRONMENT_1_NAME ENVIRONMENT_2_NAME
$ conda install -c conda-forge nb_conda_kernels -y
$ jupyter lab
```

## Built With

- [Pandas](https://pandas.pydata.org/docs/#)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/stable/index.html)
- [Statsmodels](https://www.statsmodels.org/stable/index.html#)
- [Warnings](https://docs.python.org/3/library/warnings.html)

## Author

**Samuel Zun** 
- [LinkedIn](https://www.linkedin.com/in/szun/) | [Github](https://github.com/SZun)