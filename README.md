# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Start the program and import sys module.

### Step 2: Accept the filename using command line argument (sys.argv).
 
### Step 3: Open the file in read mode.

### Step 4:  Read the contents of the file.

### Step 5: Split the contents into words and count them.

### Step 6: Display the total number of words and stop the program.

## PROGRAM:
```
a=input()
try:
    with open(a,'r') as file:
        text = file.read()
        words = text.split()
        print("Total number of words:", len(words))

except FileNotFoundError:
    print("File not found!")
```

### OUTPUT:
<img width="540" height="145" alt="image" src="https://github.com/user-attachments/assets/2662dc9c-32a4-4a53-9fd4-b9fca90af9f9" />




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
