# Data Science Project - Template Repository

## Description
Template repo to use as base/template repository for all projects. Based on Uber's repo, modified extensively to trim down to basics.


## File structure
<!-- Add as the project grows! -->
```
 ├── assets/        : Stores static files that are used in the project
 ├── code/          : Stores scripts and Jupyter notebooks
 │   └── data.py    : Python module to implement data loading functions
 │   └── utils.py   : Python module to implement utility functions
 ├── conf/          : Stores configuration/env files 
 ├── data/          : Stores data 
 │   └── raw        : Raw, immutable data, DO NOT EDIT any raw data
 │   └── processed  : Store processed data which can be used by models etc.
 ├── models         : Stores models as Pickle / serialized JSON
 ├── .gitignore     : List of files to skip tracking in git
 ├── logs/          : Stores logs 
 ├── output/        : Stores project output (plots/predictions)
 ├── README.md      : Project README

```
