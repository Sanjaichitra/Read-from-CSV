# Read-from-CSV

## AIM:
To write a python program to read content from a csv file.

## ALGORITHM:
### Step 1:
Import pandas module as pd.

### Step 2:
Using pd.read_csv() method read the CSV file.

### Step 3:
Using df.head() print the first 10 rows of the CSV file.


### Step 4:
Using df.tail() print the last 5 of the CSV file.

### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column

## PROGRAM:
 # Python program to read content from a csv file
 # Developed by: SANJAI S
 # Register Number: 212223230185
 
~~~
import pandas as pd
df = pd.read_csv('cars.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
~~~
## OUTPUT:
![Screenshot 2023-12-31 185755](https://github.com/Sanjaichitra/Read-from-CSV/assets/144870518/c09cbf23-cc5e-4825-a5cf-43d7f38089da)



## RESULT:
