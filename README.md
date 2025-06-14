# 🐼 Pandas Tutorial Notebook

This notebook is a hands-on guide to core Pandas concepts, designed for those looking to learn or revise key data manipulation techniques using Python.

## 📘 Contents

The notebook covers:

- **Masking using Booleans:** Filtering data using conditional expressions.
- **`value_counts()` Function:** Understanding frequency distribution in categorical data.
- **Plotting in Pandas:** How to visualize data directly using built-in Pandas plot functions.

## 📁 Dataset

The notebook works with a dataset called `matches.csv`. Ensure this CSV file is present in the same directory as the notebook.

```python
import numpy as np
import pandas as pd
df = pd.read_csv('/matches.csv')
type(df)


For libaries.............
pip install pandas numpy matplotlib


Requiremnets.........................................
Python 3.x

Pandas

NumPy

Matplotlib (if used in plots)

