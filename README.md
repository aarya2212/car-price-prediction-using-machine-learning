#!/usr/bin/env python
# coding: utf-8

# In[1]:


import numpy as np


# In[2]:


import numpy as np


# In[3]:


import matplotlib.pyplot as plt


# In[4]:


import seaborn as sns


# In[5]:


from sklearn.model_selection import train_test_split


# In[6]:


from sklearn.tree import DecisionTreeRegressor


# In[8]:


import pandas as pd


# In[9]:


file_path = r"C:\Users\hp\OneDrive\Desktop\cardata.xlsx" 


# In[10]:


data = pd.read_excel(file_path)


# In[11]:


data.head()


# In[12]:


data.isnull().sum()


# In[13]:


data.isnull().sum()


# In[14]:


print(data.describe())


# In[15]:


data.CarName.unique()


# In[16]:


sns.set_style("whitegrid")


# In[17]:


plt.figure(figsize=(15, 10))


# In[18]:


sns.distplot(data.price)


# In[19]:


plt.show()


# In[20]:


print(data.corr())


# In[21]:


predict = "price"


# In[22]:


data = data[["symboling", "wheelbase", "carlength", 
             "carwidth", "carheight", "curbweight", 
             "enginesize", "boreratio", "stroke", 
             "compressionratio", "horsepower", "peakrpm", 
             "citympg", "highwaympg", "price"]]


# In[24]:


sns.boxplot(df[cols[1]]);


# In[25]:


column_to_visualize ="wheelbase"


# In[28]:


file_path = r"C:\Users\hp\OneDrive\Desktop\cardata.xlsx"
df = pd.read_excel(file_path)


# In[29]:


column_to_visualize = "wheelbase"


# In[30]:


sns.boxplot(data=df, y=column_to_visualize)


# In[34]:


import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
 


