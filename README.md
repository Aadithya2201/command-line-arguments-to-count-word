# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys module

### Step 2:
using sys module,open a file with read mode

### Step 3:
read the file and split the file and stor in the variable

### Step 4:
print the length of the variable

### Step 5:
End the program
### PROGRAM:
```
"""
To write a python program for getting the word count from the contents of a file using command line arguments.
Developed by: AADITHYA R
Reference no: 23006361
"""
import sys
f=open(sys.argv[1],"r")
a=f.read().split()
print(len(a))
```

## OUTPUT:
![Screenshot 2023-12-28 142346](https://github.com/Aadithya2201/command-line-arguments-to-count-word/assets/145917810/a448562c-a8bc-4458-b626-b7a53fab4e6e)

![Screenshot 2023-12-28 142432](https://github.com/Aadithya2201/command-line-arguments-to-count-word/assets/145917810/8d5c6620-45ef-4584-a33f-1bed1ed27a69)

### TEXT FILE:
![Screenshot 2023-12-28 141436](https://github.com/Aadithya2201/command-line-arguments-to-count-word/assets/145917810/6c8bcb14-3bc6-48aa-a4ae-2c05623b7cc6)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
