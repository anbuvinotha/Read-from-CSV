# Read-from-CSV

## AIM:
To write a python program for reading content from a csv file

## ALGORITHM:
### Step 1:
Import pandas as pd
### Step 2:
Read the csv file using read_csv method
### Step 3:
Use head and tail method to get the required contents from the file
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output

## PROGRAM:
```
'''
#Developed by : Anbu Vinotha.S
#Register number : 23013363
'''
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```

## OUTPUT:
![output](<read ss.png>)

## RESULT:
This program was created successfully
