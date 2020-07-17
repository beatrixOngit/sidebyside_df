## Display multiple data frames horizontally
To be able to display data frames next to each other using IPython.
Requires jupyter and following packages: 
- IPython
- sklearn import datasets
- pandas

**One piece of caution**: if your column names are too big (see the iris example) 
then that dataframe will move to the next line. 
This works great with few columns at a time, groupbys, head(), etc.
