# SP_squirrels
Project on squirrel data for Scientific Programming.

## Data
The data contains of 3023 squirrels seen in Central Park. Details can be found at https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-10-29.

## Analyses
The file 'squirrels.ipynb' contains code for various analyses on the squirrel dataset. These analyses are
- Visualization of distribution of squirrels over the park
- Isolation Forest (IF) on a subset of the variables to get anomaly score per sample
- Unsupervised Random Forest (URF) on the same subset of variables
- Multidimensional Scaling (MDS) to visualize results from URF for different variables
- Coloring of MDS plots by anomaly scores from IF


