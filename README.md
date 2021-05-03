# Real Estate Investment Predictor
   ![image](https://user-images.githubusercontent.com/75819421/115457352-460a7e00-a1d9-11eb-91d9-0efd9641e609.png)
---

## Create and Optimize a machine learning model that can predict the next city in the Bay Area that will experience a surge in the real estate market. Furthermore, users can choose different variaties of features to see more growth scale.

For this project, we've assumed roles as Senior FinTech Analysts reporting to the SVP of Faculty Success for BCS, the developer/administrator of industry-leading online learning environments for the most respected Universities, including UC Berkeley, MIT.

SVP has tasked our pod with developing a strategy that defines pathways to successful home ownership for the company's staff and faculty.
Providing its employees "X"% cash down if purchasing in select housing markets that are still expected to demonstrate their highest rate of growth, loosely categorized as "ahead of the bell curve."

NOTE: X= could just be a straight 10%
      or
      X= (tenure/company_age)*20%
      Can exercise once every 8 years (edited) 
##  Scope
We focus on San Francisco, San Mateo, Santa Clara, Alameda, Contra Costa, Marin, Sonoma Counties. Napa, and Solano Counties have been intentionally excluded so that the data would not be diluted by cities that are of less interest to our target audience.

---
  

## Results
---

* K-means Clustering with Elbow Method
![image](https://user-images.githubusercontent.com/75819421/116847327-2d1da780-ab9f-11eb-8c13-a4d845f09381.png)
![image](https://user-images.githubusercontent.com/75819421/116847419-54747480-ab9f-11eb-9598-ebb1f21cfd1d.png)

* SVC classifier model from SKLearn's support vector machine (SVM) learning method, ...
  * The model's accuracy was assessed to be 87%
  * The model's precision was assessed to be 75% for cluster 2 and 100% for cluster 3.
  * The model's recall was assessed to be 100% for cluster 2 and 78% for cluster 3.

![](/Images/clusters_classification_report.png)    
![](/Images/.jpg)

* Neural Network Deep Learning:
  * The model's accuracy was assessed to be 93%
  * The lodel's loss was assessed to be 19%

![](/Images/nn_25_yr_mn.jpg)    
![](/Images/nn_accuracy_loss.jpg)
![](/Images/new_nn_acc_loss_graph.png)

### Question: What impact resulted from using various models?

  Accuracy and precision increased by testing different clustering methods, and different machine learning models.

  
## Summary
---
By using the K-means clustering method and our bell curve theory, we were able to cluster cities into groups that corresponds to their position on the bell curve. 
Then we use the SVM model and the neural network model to test our cluster results. Compared to the the SVM model, the neural network model was more relatable to
to our clusters by having a more accurate result.  

---

## Technologies

The application is written in Python using Pandas
The following packages are used:

Pandas - to write and run the program [Pandas documentation](https://pandas.pydata.org/docs/)

Pathlib - to create file paths [Pathlib documentation](https://docs.python.org/3/library/pathlib.html)

NumPy - for mathematical functions [NumPy documentation](https://numpy.org/doc/)

hvPlot - to create graphs [hvPlot documentation](https://hvplot.holoviz.org/)

matplotlib - to create graphs [matplotlib documentation](https://matplotlib.org/stable/contents.html)

datetime - to standardize the format of dates - [datetime documentation](https://docs.python.org/3/library/datetime.html)

DateOffset - to create a date range [DateOffset documentation](https://pandas.pydata.org/docs/reference/api/pandas.tseries.offsets.DateOffset.html)

finta - to support trading indicators - [finta documentation](https://pypi.org/project/finta/0.3.3/)

SciKit-Learn - to train models, encode data, and scale data [SciKit Learn documentation](https://scikit-learn.org/0.21/documentation.html)

---

## Installation Guide

Install the Pandas package using the following command: 'import pandas as pd'

Install the Pathlib module using the following command: 'from pathlib import Path'

Install the numpy library using the following command: 'import numpy as np'

Install the hvPlot library using the following command: 'import hvplot.pandas'

Install the matplotlib library using the following command: 'import matplotlib.pyplot as plt'

Install the datetime library using the following command: 'from datetime import datetime'

Install the DateOffset package using the following command: 'from pandas.tseries.offsets import DateOffset'

Install the finta library using the following command: 'from finta import TA'

Install the SciKit-Learn metrics libraries using the following commands: 'from sklearn import svm', 'from sklearn.svm import SVC', 'from sklearn.cluster import KMeans', 'from sklearn.decomposition import PCA', 'from sklearn.preprocessing import StandardScaler', 'from sklearn.metrics import classification_report', 'from sklearn.linear_model import LogisticRegression'


--- 

## Usage

To run this program, clone the repository onto your computer, navigate to its source folder in your terminal and launch it using the command 'jupyter lab' then either run the entire program at once, or run the cells individually (in order) as you move through the file.

---

## Contributors

Might Lee
Mightlee123@gmail.com

Susannah Slocum 
suzyslocum@gmail.com

Michael Husary
mikehoo92@yahoo.com

Konrad Kozicki
Konrad.kozicki@gmail.com

---

## License

None
