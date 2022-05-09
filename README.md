# data-visualization-using-plotly-cufflinkslin
Worked on Tesla solar panel data set and Tesla stock price data set to find the top 3 states for solar panel and  to visualize the stock price by using plotly and cufflinks library
import pandas as pd
import numpy as np
#importing plotly Library
from plotly.offline import iplot
import plotly as py
import plotly.tools as tls
import cufflinks as cf #Supporting library for plotly
py.offline.init_notebook_mode(connected=True) #Turning on notebook mode 
cf.go_offline()
#import plotly.graph_objs as go
