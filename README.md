# stats
finding mean , mode and median


import numpy as np
from scipy import stats
data = np.array([4,5,1,2,7,2,6,9,3])
dt_mean = np.mean(data) ; print ("Mean :",round(dt_mean,2))
dt_median = np.median(data) ; print ("Median :",dt_median)
dt_mode =  stats.mode(data); print ("Mode :",dt_mode[0][0]) 
