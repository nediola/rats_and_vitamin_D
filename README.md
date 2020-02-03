## The purpose of the project

The purpose of this project is to study the effect of vitamin D on rat aging using the rat lipids data.

## Dataset

The dataset ('data/lipid_data.csv') is the LC-MS results from 5 kinds of tissues (liver, muscle, plasma, cerebellum and prefrontal cortex) for 3 groups of rats: young rats, old_rats and rats which had taken vitamin D. The matching between the samples and the rats' information stores in 'data/metadata.csv'.

## Goals and Methods

Our first goal was to try several filtering and normalization methods on the lipidomic data and then calculate basic statistics (permutation test, t-test, ANOVA) to find differences between 'old rats with vitamin D' group and the 'old rats' group. These tests didn't bring us meaningful results, but you can find all the code in the file 'Normalization.ipynb'.

The second goal was to draw volcano- and PCA-plots on the normalized dataset('data/normalized_data.csv') and try to notice if older rats with vitamin D are closer to young rats than old rats. We discovered here that PCA can divide different types of tissues into the clear clusters, but can't partition rats by 3 groups. The code of this step is in the file 'Clusterization.ipynb'.

## Result

We haven't found meaningful results that vitamin D influences the age of rats' lipidom.

## System requirements

Linux/MacOS, Python 3.7, Jupyter Notebook, preinstalled Python Libraries: pandas, numpy, plotly, scipy, sklearn.
