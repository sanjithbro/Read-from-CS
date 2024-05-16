# Read-from-CSV

## AIM:
To write a python program for reading the csv file content
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```python
#To write a python program for reading content from a CSV file.
#Developed By : Sanjith.R
#Register Number : 212223230191
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![329863199-2d2a2b8f-9292-4ef2-8cf0-b6d1a6dd9502](https://github.com/sanjithbro/Read-from-CS/assets/167451460/77635f1b-addb-4331-989a-e45c57ebda4d)
## RESULT:
Thus the program is written to read the csv file.

