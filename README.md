# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2: 
Open file using open().
 
### Step 3: 
Use for loop

### Step 4:  
Use len to count number of words.

### Step 5: 
Give print.

### Step 6: 
End of the program

## PROGRAM:
```
Developed by :B.Mohamed Athil
registration no :22008533
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)
```

### OUTPUT:
![21](https://user-images.githubusercontent.com/119560261/214896312-1a3abab7-d7bf-4798-9cc0-d0019d8d2a1f.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
