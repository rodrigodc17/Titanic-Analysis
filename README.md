# Titanic-Analysis
## Starter project about the Titanic database, extracted from Kaggle.

In this project we tested some features such as manipulating and handling Data Frames, implementing functions to analyze data, and exploring data visualization with the Seaborn library.
import pandas as pd
from pandas import Series, DataFrame
# Set up of the titanic data as a Data Frame
titanic_df = pd.read_csv('/Users/rodri/Downloads/train.csv')
# Data preview
titanic_df.head()
![image](https://user-images.githubusercontent.com/61745662/218235555-154dae9f-71aa-4e0f-b4dd-48c1fa9c9789.png)
# Data structures overview
titanic_df.info()
![image](https://user-images.githubusercontent.com/61745662/218235571-1fe59196-d739-4932-a3ed-054bd8295392.png)
