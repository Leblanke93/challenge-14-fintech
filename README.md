# challenge-14-fintech

# Technologies

 Imported Libraries
 
 # Imports
 
import pandas as pd

import numpy as np

from pathlib import Path

import hvplot.pandas

import matplotlib.pyplot as plt

from sklearn import svm

from sklearn.preprocessing import StandardScaler

from pandas.tseries.offsets import DateOffset

from sklearn.metrics import classification_report

# Project direction

Background
In this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

What You're Creating
You’ll combine your new algorithmic trading skills with your existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

In a Jupyter notebook, you’ll do the following:

Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.

Adjust the input parameters to optimize the trading algorithm.

Train a new machine learning model and compare its performance to that of a baseline model.

# CONCLUSION

The SVM model did better than the Logistic regression model since the accuracy of the SVM is 55 and The LR model is 52, which makes slightly higher.
<img width="221" alt="PGN return for LR model" src="https://user-images.githubusercontent.com/90729599/152713909-da7a5712-d965-4cdf-bea3-97a9d511c90f.PNG">
<img width="319" alt="PNG of SVM model return" src="https://user-images.githubusercontent.com/90729599/152713911-72b9e7a4-e91a-4fc4-b0a1-e2d37bbcc2ee.PNG">
<img width="374" alt="LR report" src="https://user-images.githubusercontent.com/90729599/152713913-91358093-c9f1-4397-8e26-43eab4c1d3c7.PNG">
<img width="334" alt="SVM model report" src="https://user-images.githubusercontent.com/90729599/152713914-0596d067-7f1e-4be5-9792-c6330484f25e.PNG">



# Licence

Columbia Fintech Bootcamp

MIT License

Copyright (c) 2022 Leblank93

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
=======
