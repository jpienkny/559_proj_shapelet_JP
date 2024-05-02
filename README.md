EECS 559 Project Jed Pienkny

File Directory:

HR_Distances.csv - Distance between full time HR time series (73x73)
EDA_Distances.csv -  Distance between full time EDA time series (73x73)
HR_Distances_Windows.csv - Distance between full time HR time series 90s windows (73x73*15)
EDA_Distances_Windows.csv - Distance between full time EDA time series 90s windows (73x73*15)

distance_mat_extraction.ipynb - extracts distances, as I shouldn't post our dataset in a public GitHub

project_final_raw.ipynb - Methods implemented on raw data, isn't runnable w/o raw dataset

project_final_distances.ipynb - Methods implemented on distances data, is runnable w raw dataset

All requirements are most updated versions of all used Python Libraries: 

import numpy as np
import scipy.io as scio
import tqdm
import pandas as pd
import matplotlib.pyplot as plt
import os
import skimage
import csv