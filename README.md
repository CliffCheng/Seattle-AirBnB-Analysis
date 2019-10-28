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

# Where are the most expensive neighbourhoods to rent an AirBnB?
This answer is more variable for housing units but in summary the more expensive neighbourhoods are:

Queen Anne, Ballard, Lower Queen Anne, Minor, Capitol Hill, Pike Place Market, Central Business District, Belltown, and Firsthill.

# How are property types dispersed throughout Seattle?
Most of the apartments are centered around Belltown where it mainly consists businesses and residental units are less avaliable. Houses and other apartments are clustered north.

# Are there areas of potential opportunities depending on neighbourhoods?
Belltown is a high demand region with a focus on apartments. There are a lot of areas that have fewer AirBnB listings but are close to areas of high demand. The next step would be to build a model based on pricing that we can use to estimate the potential revenue of certain areas to help potential AirBnB hosts rent out their avaliable units.

# Files
The datasets used are too large to fit inside GitHub but you can find the full dataset on Kaggle (website link below). I have included a copy of the code used in this analysis. To view the full details of the analysis please refer to the Kaggle link below.

# Kaggle Website
The full set of data and analysis can be found on Kaggle's Website:

https://www.kaggle.com/cliffcheng/seattle-airbnb-intro-analysis

# Acknowledgements
I wanted to thank Udacity and my mentors in giving me this opportunity to learn. I had so much fun with this project. Credit to Kaggle for the AirBnB datasets for 2016. 
