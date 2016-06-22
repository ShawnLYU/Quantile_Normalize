
Quantile_Normalize
======== 
This function implements quantile normalization in python matrix (Pandas DataFrame)

####dependencies
1. [Numpy](http://www.numpy.org/)
2. [Pandas](http://pandas.pydata.org/pandas-docs/stable/install.html)

####data
Input data is a Pandas dataframe (df).
Each row stands for an observations and each column stands for an attribute

####usage
    from Quantile_Normalize.quantile_norm import quantileNormalize
    result = quantileNormalize(df)

####advantage
Pretty simple logic but relatively high efficiency

####references
Thanks for the following:
[Ranking of numpy array with possible duplicates](http://stackoverflow.com/questions/14671013/ranking-of-numpy-array-with-possible-duplicates)

####stack overflow
This solves the problem of [quantile normalization on pandas dataframe](http://stackoverflow.com/questions/37935920/quantile-normalization-on-pandas-dataframe)
