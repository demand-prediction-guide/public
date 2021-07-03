# A Practical Guide for Demand Prediction in Retail


# Install requirements and launch notebook:
In your command line:

```
conda env create -f DemandForecastingEnv.yml
```

```
conda activate DemandForecastingGuide
```

```
jupyter-notebook
```

# Repository Structure:


```bash

  ├── data                           
  │    ├── data_raw.csv                                                 # Raw dataset  
  │    ├── data_processed.csv                                           # Pre-processed dataset  
  │    └── results.csv                                                  # Results sumary   
  ├── notebooks                             
  │    ├── 1_Introduction.ipynb                                         # Intro
  │    ├── 2_Data Pre-Processing and Modeling Factors.ipynb             # Pre-Processing 
  │    ├── 3_Common Demand Prediction Methods.ipynb                     # Common Methods  
  │    ├── 4_Tree-Based Methods.ipynb                                   # Tree Based Methods 
  │    ├── 5_Clustering Techniques.ipynb                                # Clustering Based Methods  
  │    ├── 6_Evaluation and Visualization.ipynb                         # Evaluation 
  │    └── 7_More Advanced Methods.ipynbb                               # Advanced Methods 

