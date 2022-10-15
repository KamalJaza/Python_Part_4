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
