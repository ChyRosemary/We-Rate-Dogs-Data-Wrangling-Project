# We Rate Dogs-Data Wrangling Project
## by (ODINIGWE CHINYERE ROSEMARY)


## Dataset

> These dataset was divided into three

* The WeRateDogs Enhanced Twitter archive which contains data extracted from weratedogs twitter account, posted between November 15, 2015 and August 1, 2017.This data contains tweet id, dog ratings, dog stage and dog name that were taken from the text of the tweet.This was provided by udacity
* The image predictions dataset that was programmatically downloaded, it contains the various image predictions of dog and confidence values
* The retweet and favorite count dataset that was extracted from twitter API. This contains tweet ids and its favorite and retweet count

### Packages Used
```
import pandas as pd
import numpy as np
import requests
import os
import re

* #For gathering data from twitter API *
import tweepy
import json
from timeit import default_timer as timer

- #For Visualization - 
import matplotlib.pyplot as plt
import seaborn as sns
% matplotlib inline

```

## Data Wrangling 

> ### Assessing and Cleaning

For analysis , the above dataset was assessed both visually and programmatically. Several Quality and Tidiness issues were discovered which wouldn't have been great for my analysis, hence these issues were cleaned as seen in the Wrangle-act notebook. After cleaning, the individual dataset were merged into a master document which was used for analysis.
This process followed the **DEFINE-CODE-TEST** framework

## Key Insights

> The following questions were generated for the purpose of analysis;

* Is there any correlation between retweet_count and favorite_count?
* What is the most common tweet source?
* Is there any relationship between tweet source and retweet_count as well as favorite_count?
* Day of the week with the highest tweet
* Which dog_stage has the highest retweet and favorites?
* Top 10 dog breeds based on retweet_count and favorite_count ?
