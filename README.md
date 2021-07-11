# Kaggle-Competition-Template

Setting Up Data Science Project for Kaggle Competitions and others

Structure of Project:

```
├── LICENSE
├── .gitignore
├── requirements.txt   <- requirements file for reproducing with `pip freeze > requirements.txt`
├── data
│   ├── processed      <- final data sets for modeling
│   └── raw            <- original unprocessed data
├── logs
├── models             <- Trained serialized models, model predictions, or model summaries
├── notebooks          <- Jupyter notebooks
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
├── reports            <- Generated reports in HTML, PDF, LaTeX, etc.
├── src                <- Source code for use in project.
│   ├── config.py      <- Holding Configurations
│   ├── data           <- Scripts to get/generate data
│   │   └── dataset.py 
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   ├── models         <- Scripts to create/train/use models
│   │   ├── loss.py
│   │   ├── model.py
│   │   ├── test.py
│   │   └── train.py
│   └── visualization  <- Scripts to data visualizations
│       └── visualize.py
└── README.md
```
