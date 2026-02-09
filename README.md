# Peak prediction for energy consumption time series using XGBoost

## Overview

In this project, regression and classification via boosted trees (XGBoost) is introduced. XGBoost is applied to a particular case study, in which the peak values and peak positions for time series are estimated.
The performance of boosted trees is compared to simple baselines. 

The entire work, including the results of the study and the cleaning of data, is summarized in the `FinalReport.pdf` file. 

## Data

The project required an exploratory analysis of the data and cleaning. The raw data is taken from: https://datadryad.org/dataset/doi:10.5061/dryad.m0cfxpp2c

## Individual contribution

The work is collaborative with three other peers. My personal contributions to the project were:
* writing the theory behind XGBoost at a level for MSc students (Section 2 of the final report)
* aiding with the interpretation of the results and the discussion
* an implementation of baselines for peak prediction, to which XGBoost was compared (i.e. implementing a rolling-window peak prediction via linear regression)
