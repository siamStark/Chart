
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.metrics import mean_squared_error, r2_score 


url = "http://bit.ly/w-data"
data = pd.read_csv(url)

data.head(5)
