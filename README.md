                                                      **  # Customer_segmentation**

**1. Import Necessary Libraries**
We start by importing essential libraries for data manipulation, visualization, and machine learning:      

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.cluster import KMeans
from sklearn.preprocessing import StandardScaler
from sklearn.decomposition import PCA
from scipy.cluster.hierarchy import dendrogram, linkage


**2. Load the Dataset**
The dataset containing customer information is loaded into a Pandas DataFrame:

**3. Check for Missing Values**
We check for any missing values in the dataset to ensure data integrity:

**5. Clean Column Names**
To avoid any issues with whitespace, we strip any leading or trailing spaces from the column names:

**6. Determine Optimal Clusters**
Use the Elbow Method to identify the optimal number of clusters (k) by plotting the inertia for different values of k and selecting the point where the curve starts to flatten.

**5. Fit K-Means and Visualize Results**
Fit the K-Means model with the optimal number of clusters, assign cluster labels to the data, and visualize the customer segments using PCA for dimensionality reduction, along with bar plots to show average spending scores and annual incomes by cluster.

                                                        
