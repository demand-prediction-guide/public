# Demand Prediction in Retail - A Practical Guide to Leverage Data and Predictive Analytics


# SET-UP OPTION 1: Using Anaconda on your local machine

## Install anaconda:

Download the anaconda version which corresponds to your OS

https://www.anaconda.com/products/individual

## Install requirements and launch notebook:
In your command line:

```
$ conda env create -f DemandForecastingEnv.yml
```

```
$ conda activate DemandForecastingGuide
```

```
$ jupyter-notebook
```


# SET-UP OPTION 2: Using Google Colab

Directly start coding using the following link:

https://colab.research.google.com/notebooks/intro.ipynb#

# ACCESS NOTEBOOKS AND DATASETS:

## Clone repository:

```
$ git clone https://github.com/demand-prediction-guide/public.git
```



## Repository structure


```bash

  ├── data                           
  │    ├── data_raw.csv                                                 # Raw dataset  
  │    ├── data_processed.csv                                           # Pre-processed dataset  
  │    ├── robustness_test.csv                                          # Evaluation of split ratio robustness
  │    └── results.csv                                                  # Results sumary   
  ├── notebooks                             
  │    ├── 1_Introduction.ipynb                                         # Intro
  │    ├── 2_Data Pre-Processing and Modeling Factors.ipynb             # Pre-Processing 
  │    ├── 3_Common Demand Prediction Methods.ipynb                     # Common Methods  
  │    ├── 4_Tree-Based Methods.ipynb                                   # Tree Based Methods 
  │    ├── 5_Clustering Techniques.ipynb                                # Clustering Based Methods  
  │    ├── 6_Evaluation and Visualization.ipynb                         # Evaluation 
  │    └── 7_More Advanced Methods.ipynbb                               # Advanced Methods 

