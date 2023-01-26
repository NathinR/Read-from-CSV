# Read-from-CSV

## AIM:
To write a python program to read data from CSV file.

## ALGORITHM:

### Step 1:
Start the python.
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.

## PROGRAM:

'''

Developed By : Nathin R

Referance No. : 22008510

'''

import pandas as pd

f=pd.read_csv('nba.csv')

print(f.head(10))

print(f.tail())

print('Row:',len(f.axes[0]))

print('Col:',len(f.axes[1]))

## OUTPUT:

![Screenshot_20230126_061056](https://user-images.githubusercontent.com/118679646/214837981-884de253-6ab2-4145-9420-ccb7469e587e.png)


## RESULT:
