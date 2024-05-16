# Read-from-CSV

## AIM:

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
![329863199-2d2a2b8f-9292-4ef2-8cf0-b6d1a6dd9502](https://github.com/drgbhuvaneswari/Read-from-CSV/assets/167451460/ee1ec5e5-6849-47c6-9589-b6b30dc9935b)

## RESULT:
Thus the program is written to read the csv file.

