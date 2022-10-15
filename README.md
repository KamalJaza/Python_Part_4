# Python-week-4
# Pandas
## loc() and iloc()
- loc() and iloc() are essential Pandas methods used for filtering, selecting, and manipulating data. They are quick, fast, easy to read, and sometimes interchangeable.
- loc() and iloc() method are used to overcome inconsistencies in calling data.
### loc() function
- The loc() function is label based (explicit index) data selecting method which means that we have to pass the name of the row or column which we want to select.
- This method includes the last element of the range passed in it.
- loc() can accept the boolean data unlike iloc().
### iloc() function
- The iloc() function is an indexed-based (implicit index) selecting method which means that we have to pass an integer index in the method to select a specific row/column.
- This method does not include the last element of the range passed in it.
- iloc() does not accept the boolean data unlike loc().

## Pandas DataFrame
- DataFrame is a 2 dimensional data structure, like a 2 dimensional array, or a table with rows and columns
- DataFrames are similar to SQL tables or the spreadsheets that you work with in Excel or Calc. In many cases, DataFrames are faster, easier to use, and more powerful than tables or spreadsheets because they’re an integral part of the Python and NumPy ecosystems.
- DataFrames are widely used in data science, machine learning, scientific computing, and many other data-intensive fields.

## Data Preparation and Exploration
- Call the Dataset using data.read_csv()
- Show the data fro the top ot from the bottom using data.head() or data.tail()
- Display all the information about dataset using data,info()
- Check missing value and count it using data.isnull().sum()
## Exploration the Information in Data
- The number of rows using data.shape()
- The name of the columns using data.column()
- The index using data.index()
- Average using data.mean()
- Minimum and maximum value from the data using data.min() or data.max
- Mode of the data using data.mode()
- View the unique data from some column and know the count of it
