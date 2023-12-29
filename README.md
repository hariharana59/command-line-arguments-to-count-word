# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2: 
Pass the filename as the first argument after the name of script. Open the file as sys.argv[0]

### Step 3: 
Read the file using read() method.

### Step 4:  
Use split() method to split the file content into words.

### Step 5: 
Use len() to find the total words.

### Step 6: 
Run the program to determine the number of words in the file created.


## PROGRAM:
```
#To find the word count using command line arguments
#Developed by : Hariharan A
#Reg no : 212223110013

import sys
fp= open(sys.argv[0])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```


### OUTPUT:
![image](https://github.com/hariharana59/command-line-arguments-to-count-word/assets/144980130/0758b789-9739-4e92-a1e4-2a2ac039f550)

![image](https://github.com/hariharana59/command-line-arguments-to-count-word/assets/144980130/9984de2b-868a-4459-8f36-314ccd69abf2)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
