# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create two files with extension .py and .txt

### Step 2:
Import sys in the file with .py extension

### Step 3:
Give some input words in the file with .txt extension

### Step 4:
Save the files

### Step 5:
Open terminal and choose Command prompt.

### Step 6:
Run the program and get the output
## PROGRAM:
##student name:sivaram R
##reference no:22008680
```
import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word]=1
            else:
                count[word]+=1
print(count)
f.close
```
### OUTPUT:



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
