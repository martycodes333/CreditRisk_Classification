# Credit Risk Classification / Module 12 Challenge
---

This is a code created with the assistance of Jupyter Lab Notebook used with the assitance of Pandas to create a credit risk classification model thats trained and tested based on historical lending data to determine a healthy-loan from a high-risk loan.
## Technologies

This project uses python 3.7 with the following packages:

* [Pandas](https://github.com/pandas-dev/pandas) - Pandas is an open-source library that offers easy-to-use data analysis tools for Python.

* [Jupyter Lab](https://jupyter.org) - For an intuitive notebook IDE

* [scikit-learn](https://scikit-learn.org/stable/) - For sofisticated machine learning models


 
---

## Installation Guide

Before running the application first install the following:


* [Install] Anaconda with Python 3.7+(https://docs.anaconda.com/anaconda/install/)
You should always be in a conda dev environment when launching JupyterLab.



---

## Install/Import the following libraries and dependencies 

```python
# Install the required libraries
conda install -c conda-forge imbalanced-learn
conda install -c conda-forge pydotplus

# Import the modules
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings
warnings.filterwarnings('ignore')
```
---

## Usage

To view the credit_risk_resampling.ipynb, open file via Jupyter Lab

```conda activate dev
cd <location of (credit_risk_resampling.ipynb)>
jupyter lab
```

Upon launching the Jupyter Lab NOTEBOOK you will be greeted with the following prompts.

![Credit Risk Intro](sampler1.png)


As Well as the following confusion matrix visualizations

![Confusion Matrix](confusionmatrix.png)



---

## Contributors

Brought to you by MartyCodes333 (martique.henton@gmail.com) with the help of 2021 UW FinTech Bootcamp Instructors, TA's and Fellow Classmates