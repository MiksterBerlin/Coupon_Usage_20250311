Coupon Acceptance by Costumers based on several conditions.

Overview

This Project gives tries to provide some inside on the conditions (time of day, driving alone or with a passenger), behaviors (montly frequency of visiting a bar and/or a coffee shop) and demographics (gender, age and/or income level) that influence customer behaviors.

Variables in Dataset

Demographics (age, income, marital status) Conditions (driving destination, passengers, weather, time of day) Coupon specific variables (expiration time, type of establishment) Behaviors (frequency of coffee shop visits, restaurant preferences) Acceptance of Coupon (whether the driver accepted the coupon or not)

Packages

import plotly.express as px import matplotlib.pyplot as plt import seaborn as sns import pandas as pd import numpy as np

Key Results

The highest acceptance rates occur at 10 AM (64.07%) and 2 PM (54.79%), suggesting that coffee consumption is more frequent during these hours. Impact of Temperature: At Temparatures of about 80F, Drivers are more likely to accept Coupons independent of the type, Income: Drivers earning less than $50K accept bar and/or coffee house coupons more frequently compared to income levels of >$50,000. Travel time to Coupon locations: Coffee House Coupons for locations within a 5min drive are accepted more often than those for locations that are 15min away.

Processing

Open the Jupyter Notebook:

jupyter notebook prompt.ipynb

Run all cells in order to generate the results and visualizations.

Next Steps & Recommendations This dataset is useful to help target certain costumers more accurately and predict coupon acceptance with higher accuracy to prevent sending too many Coupons.
