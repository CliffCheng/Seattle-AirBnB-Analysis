Seattle-AirBnB-Analysis

# Installation
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
from decimal import Decimal
import datetime
import folium #Longitude and Lattitude mapping.
import seaborn as sns
import os
import folium
from folium import plugins
from folium.plugins import MarkerCluster #To be able to cluster our individual data points on folium.
from IPython.display import HTML, display

# Project Motivaton

I recently visited Seattle with a number of good friends and had nothing but positive comments about the city. I grew up in the San Francisco/Bay Area all my life and when I stepped foot in Seattle I saw it as a fresh start with exciting new opportunities. In this notebook I will be taking my first step into data science so what better data to explore than with the city that started my curiosity into tech.

I have three questions I want to answer with this dataset.

Where are the most expensive neighbourhoods to rent an AirBnB?

How are property types dispersed throughout Seattle?

Are there areas of potential opportunities depending on neighbourhoods?

# Files
The datasets used are too large to fit inside GitHub but you can find the full dataset on Kaggle (website link below). I have included a copy of the code used in this analysis. To view the full details of the analysis please refer to the Kaggle link below.

# Kaggle Website
The full set of data and analysis can be found on Kaggle's Website:

https://www.kaggle.com/cliffcheng/seattle-airbnb-intro-analysis

# Acknowledgements
I wanted to thank Udacity and my mentors in giving me this opportunity to learn. I had so much fun with this project. Credit to Kaggle for the AirBnB datasets for 2016. 
