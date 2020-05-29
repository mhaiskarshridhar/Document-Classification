# Document-Classificaiton
Recommendation system to suggest similar websites as per required description


Necessary Libraries:

from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.cluster import KMeans
import re
import string
import pandas as pd
from functools import reduce
from math import log