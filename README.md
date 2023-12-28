# Read-from-CSV
## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
Display the result.

## PROGRAM:
```
Developed by:thenmozhi
Register No: 212223100059

To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```
## OUTPUT:

![WhatsApp Image 2023-12-16 at 10 44 26_28f20f6a](https://github.com/AnnaLahari/Read-from-CSV/assets/149365425/6e404520-5f78-4c89-a061-6a6b3bf80f39)


## RESULT:
Thus python program for reading content from a CSV file is successful.
