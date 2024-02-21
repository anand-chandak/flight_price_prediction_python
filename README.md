I will take you a small journey of technicalities:

unique(): To see all the unique values in the series.
nunique(): Gives count of all unique values

value_counts(): Gives feature name and count of values in that feature

df.drop(): Unnecessary column removel
df.duplicated().sum(): Count of duplicated rows
df.drop_duplicates(): Removes duplicate rows

df.isnull().sum(): Count of records having null value
df.dropna(): Removes all rows having nan values

df.rename(): Renames column names, we provide dictionary to it.
df.info(): Give info includes name, datatypes, number of vales.
astype(): For typecasting

df["series_name"]: columnwise indexing
df.loc["row_name']: Row wise indexing
df.iloc[:,:]: Rowwise indexing providing integer value

strip(): To remove white spaces from both ends of the string.
lstrip() & rstrip(): Left and right respectively
title():Makes first alphabate of every word in a string capital
capitize(): Makes first sentence of a sentence capital
upper() & lower(): Convert entire string to upper and lower case respectively.

df[ser_name].factorize():[0]: Converts string type column into numerical column. Its result is passed to corr() which 
is used in headmap() creation.
df.copy(): Creates copy of dataframe



