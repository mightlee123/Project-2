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

* SVC classifier model from SKLearn's support vector machine (SVM) learning method, ...
  * The model's accuracy was assessed to be 
  * The model's precision was assessed to be  for (0) and  for (1).
  * The model's recall was assessed to be  for (0) and  for (1).

![](/Images/.jpg)    
![](/Images/.jpg)


* Logistic Regression Model:
  * The model's accuracy was assessed to be 55%
  * The model's precision was assessed to be 37% for (-1) and 56% for (1).
  * The model's recall was assessed to be 3% for (-1) and 96% for (1).

![](/Images/.jpg)    
![](/Images/.jpg)


* Linear Regression Model:
  * The model's accuracy was assessed to be 
  * The model's precision was assessed to be  for (0) and  for (1).
  * The model's recall was assessed to be  for (0) and  for (1).

![](/Images/.jpg)    
![](/Images/.jpg)

* Random Forest Regression Model:
  * The model's accuracy was assessed to be 
  * The model's precision was assessed to be  for (0) and  for (1).
  * The model's recall was assessed to be  for (0) and  for (1).

![](/Images/.jpg)    
![](/Images/.jpg)
    
### Question: What impact resulted from using various models?

  Accuracy and precision increased by increasing the training window. Recall increased for the (1) values, but decreased for the (-1) values.
  

### Questions: Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?

  
## Summary
---

### Original Model:
![](/Images/.jpg)    

### Tuned Model:
![](/Images/.jpg)    

### Logistic Regression Model:
![](/Images/.jpg)    

---

## Technologies

The application is written in Python using Pandas
The following packages are used:

Pandas - to write and run the program [Pandas documentation](https://pandas.pydata.org/docs/)

Pathlib - to create file paths [Pathlib documentation](https://docs.python.org/3/library/pathlib.html)

NumPy - for mathematical functions [NumPy documentation](https://numpy.org/doc/)

hvPlot - to create graphs [hvPlot documentation](https://hvplot.holoviz.org/)

matplotlib - to create graphs [matplotlib documentation](https://matplotlib.org/stable/contents.html)

DateOffset - to create a date range [DateOffset documentation](https://pandas.pydata.org/docs/reference/api/pandas.tseries.offsets.DateOffset.html)

SciKit-Learn - to train models, encode data, and scale data [SciKit Learn documentation](https://scikit-learn.org/0.21/documentation.html)


---

## Installation Guide

Install the Pandas package using the following command: 'import pandas as pd'

Install the Pathlib module using the following command: 'from pathlib import Path'

Install the numpy library using the following command: 'import numpy as np'

Install the hvPlot library using the following command: 'import hvplot.pandas'

Install the matplotlib library using the following command: 'import matplotlib.pyplot as plt'

Install the DateOffset package usi8ng the following command: 'from pandas.tseries.offsets import DateOffset'

Install the SciKit-Learn metrics libraries using the following commands: 'from sklearn import svm', 'from sklearn.preprocessing import StandardScaler', 'from sklearn.metrics import classification_report', 'from sklearn.linear_model import LogisticRegression'


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
