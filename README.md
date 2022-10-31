# Mice Protein Expression


```python
import pandas as pd

from sklearn.model_selection import train_test_split

from sklearn.impute import SimpleImputer

from sklearn.preprocessing import OneHotEncoder, MinMaxScaler

from sklearn.compose import ColumnTransformer, make_column_transformer

from sklearn.pipeline import make_pipeline

from sklearn.feature_selection import SelectPercentile, chi2

import seaborn as sns

import matplotlib.pyplot as plt
```
