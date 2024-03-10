# Linear Regression Model (Bike Sharing Case Study)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) [![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

In this assignment, I have built a multiple linear regression model to predict shared bike demand, aiding BoomBikes (a bike rental company) in adjusting their post-pandemic strategy based on demand dynamics.

Key points:  
* Prepped the data for modelling, mapped choice variables and created dummy variables for categorical var.  
* Split (train_size 0.7) and scaled the data using scikit-learn. 
* Using RFE, we’ve built 5 models with the final model presenting R-Square (81%) and Adjusted R-square (81%). Our VIF is within the acceptable range i.e <5
* Performed Residual analysis and Model Evaluation

Found some interesting insights! The key one being that most bike-rentals happen when the **weather is _Clear_, during Fall season (_September!_) and during weekdays (esp. _Thursday_)** . More on that in the notebook.

This one was a bit tough, but fun :) 

Download dataset by clicking [here](https://drive.google.com/drive/folders/1QF52BLUjgmJ6kO11-Psx18BSlJFL-16d?usp=sharing).

License: Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg (http://dx.doi.org/10.1007/s13748-013-0040-3)
