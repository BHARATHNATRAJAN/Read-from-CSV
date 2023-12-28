# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
mport pandas as pd
### Step 2:
 read the csv file using read_csv method.
### Step 3:
use head and tail method to get the required contents from the file
### Step 4:
use len() method to count the number of rows and columns
### Step 5:
 print the output

## PROGRAM:
```
import pandas as pd
df = pd.read_csv('datacsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of colunms:",len(df.axes[1])
```

## OUTPUT:
![image](https://github.com/BHARATHNATRAJAN/Read-from-CSV/assets/147473529/0554f0d5-4657-4cba-b9db-72816bbf5e25)

## RESULT:
Thus the result was successfully verified
