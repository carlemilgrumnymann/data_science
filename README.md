# data_science
Data science exam from spring 2026

This repository contains the files and data for the data science exam by Laura and Carl Emil

The data folder contains all the data as csv's
The "full_analysis_linear_lasso" file contains all of the data wrangling steps, exploratory modelling and most of the modelling. The only things not included in that notebook are:
The full-iteration BART models, they are in the "Bart_from_ucloud" notebook, which was on on ucloud using 8 cores, to parallelize the crossvlaidation of these more demanding models
And the visualization code, the final visualizations for the paper were done in r, code can be found in the "data_science_viz.rmd" 

In the results folder, the two files directly in the folder are results from the local run, that means form running the "full_analysis_linear_lasso" until the BART part. In the "big_BART_from_ucloud" folder, the resulting dataframes from running the "Bart_from_ucloud" notebook are saved. 