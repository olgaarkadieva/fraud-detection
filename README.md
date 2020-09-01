# Credit Card fraud Detection using Python and Jupyter Notebook


Credit card fraud is a growing issue with many challenges including temporal drift and heavy class imbalance. This project attempts to tackle class imbalance using state-of-the-art techniques including Adaptive Synethtic Sampling Approach (ADASYN) and Synethetic Minority Oversampling Technique (SMOTE).

In this project i am using Sql Lite data base to retrieve data from [database](transactions.db)

After loading data from [db](transactions.db) , i am creating DataFrame ##corr function which computes pairwise correlation of columns, excluding NA/null values.

with the help of seaborn library i am plotting a rectangular data as a color-encoded matrix.

For analysis of Data i am using SAS 

in python we have to use saspy package that allows Python coders to access SAS data and analytics capabilities.
 