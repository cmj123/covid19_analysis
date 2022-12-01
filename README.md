# COVID-19 Interactive Analysis Dashboard

A Web App to interact and visualize the analysis on COVID 19 spread across the world. 

App is deployed in Heroku, click the link to access it : [Open in Heroku](Provide your site URL here) 

## Summary

Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus. Most people infected with the COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment. Older people, and those with underlying medical problems like cardiovascular disease, diabetes, chronic respiratory disease, and cancer are more likely to develop serious illness. The best way to prevent and slow down transmission is to be well informed about the COVID-19 virus, the disease it causes and how it spreads. Protect yourself and others from infection by washing your hands or using an alcohol based rub frequently and not touching your face. The COVID-19 virus spreads primarily through droplets of saliva or discharge from the nose when an infected person coughs or sneezes, so it’s important that you also practice respiratory etiquette (for example, by coughing into a flexed elbow).

In this notebook, we'll explore the dataset which is maintained by John Hopkins CSSE (updated every 24 hours).

## Data

I gathered my data from the 2019 Novel Coronavirus COVID-19 Data repository by John Hopkins CSSE.
Refer below : 
https://github.com/CSSEGISandData/COVID-19

The data here gets updated every 24 hours from the official sources. I accessed the raw files from thecsse_covid_19_time_series directory.

## Pre-requisites

The project was developed using python 3.8.3 with the following packages.
- Pandas
- Numpy
- matplotlib
- plotly
- ipywidgets
- folium
- voila
- voila-material

Installation with pip:

```bash
pip install -r requirements.txt
```

## Getting Started
Open the terminal in you machine and run the following command to access the web application in your localhost.
```bash
voila ./notebooks/covid19_dashboard.ipynb --template=material
```


## Files
- notebooks/covid19_analysis.ipynb : Jupyter Notebook with all the analysis done on COVID 19 dataset.
- notebooks/covid19_dashboard.ipynb : Jupyter Notebook with all the necessary analysis on COVID 19 dataset.(Both the notebooks are same except this one contains the codes which are explicitly required for Dashboard only).
- requirements.txt : pre-requiste libraries for the project.
- Procfile : To trigger the app in Heroku.
