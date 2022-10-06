# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: imort sys

### Step 2: open the file in read mood
 
### Step 3: use the for loop

### Step 4:  use len function to count the number of words

### Step 5: print the statement " word count in file = "

### Step 6: run the programe to get the output

## PROGRAM:
```python 
developed by : Naveenaa A.K
Register number: 22003091

import sys
count= 0
with open(sys.argv[0],'r') as f:
    for line in f:
        word=line.split()
        count+=len(word)
print("word count in file = ",count)
```

### OUTPUT:
![text file](https://user-images.githubusercontent.com/113497406/194259592-281ecb60-87e9-4698-9829-9a59f1565225.png)
![output](https://user-images.githubusercontent.com/113497406/194259681-1e6164c0-0070-4b82-bc33-63aed0b4e92e.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
