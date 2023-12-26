# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
start the program
### Step 2: 
 import the file
### Step 3: 
open the file
### Step 4:  
write the function to counts the words
### Step 5: 
print the result
### Step 6: 
Execute the program
## PROGRAM:
```
Developed by: Nirosha M
Register No : 23014438

import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close

```
### OUTPUT:
![Alt text](<Annotation 2023-12-26 092908.png>)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
