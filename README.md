# Challenge-14
Machine learning trading bot
# history 50 > terminal_history.txt

# Financial advisor- Machine learning trading bot
Enhances the existing trading signals with machine learning algorithms that can adapt to new data.
## Technologies

import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
---

## Installation Guide
run program using jupyterlab

---

## Usage
Improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market.




* Step 1: Establish a Baseline Performance.

* Step 2: Tune the Baseline Trading Algorithm.

* Step 3: Evaluate a New Machine Learning Classifier.

* Step 4: Create an Evaluation Report

*SVM-plot and  LR-plot*
![SVM](https://github.com/MxP05/Challenge-14/blob/main/Resources/svm.png?raw=true)
![LR](https://github.com/MxP05/Challenge-14/blob/main/Resources/lrplot.png?raw=true)
---
## Summary evaluation
baseline algo accuracy score is .54
![Base](https://github.com/MxP05/Challenge-14/blob/main/Resources/base.png?raw=true)

changing the ending period for the traning data from 3 to 12 months, increased the score to .57
![12Months](https://github.com/MxP05/Challenge-14/blob/main/Resources/12month.png?raw=true)
Tuned algo accuracy score is .55 when chanching SMA short to 3, and long to 90
![SMA](https://github.com/MxP05/Challenge-14/blob/main/Resources/sma.png?raw=true)

The new model, has both the 12 months and the updated sma feature however it their is no differnce in accuracy score .57 when compared to the 12 month training score
![New model](https://github.com/MxP05/Challenge-14/blob/main/Resources/new.png?raw=true)

## Contributors

MxP05

---

## License
Enhances the existing trading signals with machine learning algorithms that can adapt to new data.