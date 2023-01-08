SWBIO DTP Data Science and Machine Learning 2022/2023
Individual Project - Luca G. Hahn
Social complexity in ancient civilisations

![image](https://user-images.githubusercontent.com/110464445/210548477-6e2e429a-2acd-4f11-a1cf-780f2a07ab67.png)

README file with instructions to successfully run the code 

(1) Data

At the beginning, download and import the data used in this project. 

#download the social complexity data set which can be obtained from the SESHAT database, and it is also available on "Kaggle")
data set from "SESHAT data base": http://seshatdatabank.info/datasets/social-complexity-dataset/
data set from "Kaggle": https://www.kaggle.com/datasets/usharengaraju/social-complexity-dataset-ancient-civilization 

#read the data set into a notebook in the Jupyter Lab interface (version 2.1.5) for Python 
social = pd.read_csv(SocialComplexity3.csv")

(2) Libraries

Then import libraries needed for data exploration. 

#import pandas, a data analysis and manipulation tool
import pandas as pd

#import matplotlib, a library for data visualisation
import matplotlib.pyplot as plt

#import seaborn, a library for data visualisation based on matplotlib
import seaborn as sns

#import requests for importing the data set from GitHub 
import requests

#import io for importing the data set from GitHub
import io

#import the following libraries for the Principal Components Analysis 
from sklearn import decomposition
from sklearn import datasets
from sklearn.preprocessing import scale
from sklearn.preprocessing import StandardScaler
import numpy as np
from pandas import DataFrame

(3) Follow the code chronologically to create figures for data visualisation. The code generates six figures that depict different aspects of the data. 

(4) For further reading, some of the following references might be of interest: 

1. Turchin P, Currie TE, Whitehouse H, François P, Feeney K, Mullins D, et al. Quantitative historical analysis uncovers a single dimension of complexity that structures global variation in human social organization. Proc Natl Acad Sci U S A. 2017;115(2):E144–51. 
2. 	Turchin P, Brennan R, Currie TE, Feeney KC, François P, Hoyer D, et al. Seshat: The Global History Databank. Cliodynamics. 2015;6(1):77–107. 
3. 	Whitehouse H, François P, Turchin P. The role of ritual in the evolution of social complexity: Five predictions and a drum roll. Cliodynamics. 2015;6(2):199–210. 






