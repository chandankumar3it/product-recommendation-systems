# Product Recommendation Systems
his is Product Recommendation Systems where we will work with the Amazon product dataset for this project. The dataset contains ratings of different products. It does not include information about the products or reviews to avoid bias while building the model.

## Amazon Product Recommendation

## Installation ##

1. Download .ipybn file and open in colab

2. You can install with:

```bash
!pip install ipywidgets
```

3. Import neccessory libraries if its not available in .ipybn file
```bash
!pip install ipywidgets
import pandas as pd
import numpy as np
import nltk
nltk.download('wordnet')
nltk.download('stopwords')
from nltk.corpus import stopwords
from nltk.stem import WordNetLemmatizer
import re

import ipywidgets as widgets
from IPython.display import display

#Visualization
import matplotlib.pyplot as plt
import seaborn as sns
from collections import Counter
from textblob import TextBlob

#Feature Engineering
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.preprocessing import LabelEncoder

#Model
from sklearn.metrics.pairwise import cosine_similarity
```

4. Download dataset and update the path
```bash
df = pd.read_csv("../your/local/or/google/colab/path/....csv")
```

5. Run the .ipybn file colab



This will provider user interface where user can enter product name and based on product name it will show the result of preferences.


## Laptop Product Recommendation
## Myntra Product Recommendation
