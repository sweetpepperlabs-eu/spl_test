---
layout: post
title: Data Science with Python
subtitle: From data cleaning to machine learning models
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [data-science, python, pandas, numpy, matplotlib]
author: lebuu_eu
---

Data science has become one of the most sought-after skills in the tech industry. Python, with its rich ecosystem of libraries, has emerged as the go-to language for data analysis and machine learning.

## Essential Python Libraries

### Pandas
For data manipulation and analysis:

```python
import pandas as pd

# Read data
df = pd.read_csv('data.csv')

# Basic operations
df.head()
df.describe()
df.groupby('category').mean()
```

### NumPy
For numerical computing:

```python
import numpy as np

# Create arrays
arr = np.array([1, 2, 3, 4, 5])
matrix = np.random.randn(3, 3)

# Mathematical operations
mean = np.mean(arr)
std = np.std(arr)
```

### Matplotlib & Seaborn
For data visualization:

```python
import matplotlib.pyplot as plt
import seaborn as sns

# Create plots
plt.figure(figsize=(10, 6))
sns.scatterplot(data=df, x='x', y='y')
plt.title('Data Visualization')
plt.show()
```

## Data Science Workflow

### 1. Data Collection
- APIs, databases, web scraping
- Public datasets (Kaggle, UCI)
- Internal company data

### 2. Data Cleaning
- Handle missing values
- Remove duplicates
- Fix data types
- Address outliers

### 3. Exploratory Data Analysis
- Statistical summaries
- Data visualization
- Correlation analysis
- Feature engineering

### 4. Model Building
- Split data (train/test)
- Choose algorithms
- Train models
- Evaluate performance

### 5. Deployment
- Model serialization
- API development
- Monitoring
- Updates

## Popular Algorithms

### Supervised Learning
- **Linear Regression**: For continuous outcomes
- **Logistic Regression**: For binary classification
- **Random Forest**: For complex patterns
- **Support Vector Machines**: For high-dimensional data

### Unsupervised Learning
- **K-Means**: For clustering
- **Principal Component Analysis**: For dimensionality reduction
- **Association Rules**: For pattern discovery

## Tools and Platforms

- **Jupyter Notebooks**: Interactive development
- **Google Colab**: Cloud-based notebooks
- **Anaconda**: Package management
- **Scikit-learn**: Machine learning library

Data science is transforming how businesses make decisions, and Python provides the perfect toolkit for this revolution. 