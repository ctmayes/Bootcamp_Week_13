# Bootcamp_Week_13

# Venture Funding with Deep Learning

This program is designed create a model that predicts whether applicants will be successful if funded by Alphabet Soup, a venture capital firm. The applicants_data CSV file in the resources folder contains more than 34,000 organizations that have received funding from Alphabet Soup over the years. The file contains a variety of information about each business, including whether or not it ultimately became successful. This program utilizes that information to create a binary classifier model that will predict whether an applicant will become a successful business in the future, hopefully improving future operations for our venture capital firm.

## Technologies

Within this program, we will make use of the following external python modules:

  -- pandas
  -- pathlib
  -- tensorflow
  -- sklearn
  
  Additionally, this program was created within a python v3.7 build, and its relevant dependencies.

---

## Installation Guide

To utilize this program, within your terminal you will have to install the required libraries. Within your terminal, input the following commands:

```python
pip install pandas
```

```python
pip install pathlib
```

```python
pip install tensorflow
```

```python
pip install -U scikit-learn
```

At the beginning of the *venture_funding_with_deep_learning.ipynb* file, the technologies are calling in with this code:

```
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
```

---

## Usage

To operate this program, open up your terminal of choice and navigate to the directory in which you have downloaded the files within this repository. Open Jupyter Lab with the command: 

```python
jupyter lab
```  

This should open jupyter lab to the filepath in which you have the repo file, and you simply need double click the *venture_funding_with_deep_learning.ipynb* file to open it. Upon opening, select the menu button with two right facing arrows at the top of the notebook, which will run the entire file. It will ask you to confirm you wish to restart the file, to which you will confirm. Wait a few moments for the program to operate as intended, and peruse the resulting data at your leisure. If you wish, simply skip to the end for my analysis of the preceding information. 

---

## Contributors

Colton Mayes ctmayes@gmail.com

---

## License

This code is created for educational purposes, and it usage therein has no commerical application. It is designated as free-use thusly, and shall remain as such.