# Pharma clinical mouse trial

## Background
This project explores data from a sample anti-cancer pharmaceutical clincal trial. The data reflects clinical drug trials in mice aimed at screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. 

In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of a "drug of interest" - Capomulin - versus the other treatment regimens. 

Data analysis was done within a jupyter notebook, with some summary graphs produced using the Matplotlib library for Python. 

## General Observations
1. Capomulin and Ramicane both had the lowest overall average tumor volumes across all datapoints, as well as relatively low variance, standard deviation, and SEM - suggesting that the results for those two regimens were more positive and more consistent than the other regimens studied.

2. Looking at the tumor growth in one of the Capomulin mice (Mouse t565), the results indicate that Capomulin does inhibit tumor growth, but only to a certain point (in this case, between time points 10 and 30). After that, the effectiveness of the drug seems to plateau tumor growth starts to increase again, even with the regimen.

3. Looking at the data for the Capomulin mice, there is a positive correleation between the each mouse's weight and the volume of the tumor, meaning the larger the mouse, the larger the tumor.