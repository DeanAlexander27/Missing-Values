# Missing-Values
What if the dataset have any missing values? how to handle it? 
how to imputation a new value to get into the process of machine learning?
how to measure error of accuracy ?

# Here's the way
Before we start, we need to know about typical of Missing Values, so here it is.
### Types of Missing Values:
- MNAR : Missing not at random is a type of NA where the cause of NA depends on the variable that has the NA value itself
- MAR : Missing at random is a type of NA in which the NA value does not depend on the variable that has the NA value, but depends on other variables in the data.
- MCAR : Missing Values which do not depend on any variable. Generally the cause of NA in this type is human error, technical error in the device or when inputting data, etc

# Treatment Missing Values in general

- Delete row. If the total number of NA data as a whole is <5%. Be careful when deleting rows because the more rows you remove, the more observations you lose which could provide important information to the data
- Delete column. If the total value of NA in a column is usually missing a lot (generally > 50%)
- Carry out imputation by filling in NA values with a certain value (you can use a business approach or a statistical approach).
