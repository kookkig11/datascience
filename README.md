### Subject : Data Science 📄

> work on anaconda : jupyter notebook
``` bash
## Simple Code

# init
import pandas as pd
import numpy

# open csv file to analysis ✨
data_name = pd.read_csv('file_name.csv')
data_name


# set index
data_name = data_name.set_index('column_name')

# check size of row and column
# 📌 or you can check data(row), column
row = len(data_name)
column = len(data_name.columns)

# check all data on this column
data_name['column_name']

# substring
data_name['column_name'].str.extract("str_expression")

# 🔥🔥 show data that you want to see [select your choice !]
data_name.loc[ row_that_you_want_to_see , column_that_you_want_to_see ]

row_that_you_want_to_see >> ['row_name1', 'row_name2']
                         >> expression_data = medal['summer'] > 24    
column_that_you_want_to_see >> ['col_name1', 'col_name2']
                            >> 'start_col' : 'end_col'
```
