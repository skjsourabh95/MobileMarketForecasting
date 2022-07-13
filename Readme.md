# Mobile Market Forecasting
- Generate time-series forecasts with the highest accuracy predictions possible for the financial variables given.

## Tech Stack
- [Anaconda Python3](https://www.anaconda.com/distribution/)


## Installation
### Installing Required modules in conda environment
```cmd
- conda create -n forecast python==3.7.3 -y
- conda activate forecast
- pip install jupyter tensorflow==1.14.0 Keras==2.2.4 xlrd==1.2.0 matplotlib==3.0.3 statsmodels==0.9.0 pandas==0.24.2 pickleshare==0.7.5 numpy==1.17.4 
```

## Verfication
```cmd
- Open a conda prompt
- conda activate forecast # new conda terminal
- cd /path/to/project/directory 
- jupyter notebook #type this command after activating conda environment
- Open the jupyter notebooks with the financial variable names and the instructions to run them are present there.
- MakePredictions.ipynb- This contains all the models and it can be run to fetch predictions from various models saved.
```

## NOTES
- For guidelines,strategy and intuition involved follow the report.pdf .
