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
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1].

### Step 3: 
Read the file using read() method.

### Step 4:  
Use split() method to split the file content into words.

### Step 5: 
Use len() to find the total words.

### Step 6: 
Run the program to determine the number of words in the file created.

## PROGRAM:
```python
import sys
with open(sys.argv[1],'r') as f:
    num_words =0
    for i in f:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))

```

### OUTPUT:
![out1](https://user-images.githubusercontent.com/119401150/215282307-05e624f4-81f4-4bd3-86dd-2e5c8694e2b5.png)

![](out1.png)![out2](https://user-images.githubusercontent.com/119401150/215282315-a52a0781-4034-41c7-899c-6098e337c3c6.png)

![](out2.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
