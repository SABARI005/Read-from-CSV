# Read-from-CSV

## AIM:

## ALGORITHM:
Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_csv method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns

Step 5:
Print the output:
## PROGRAM:
```
Developed by:SABARI S
Ref.no:22008698

import pandas as pd
f=pd.read_csv("/content/nba (2).csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:
![mmm](https://user-images.githubusercontent.com/118660461/215701133-88148392-0636-41d2-8745-c3bee681236c.png)



## RESULT:
Thus a python program is written to read the contents of a CSV file.
