# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np

### Step 2: 
 Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program
## PROGRAM:
```
program to find the number of words in a text file
Developed by : STEPHEN RAJ.Y
Register number : 212223230217

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:
![Screenshot 2024-05-09 111204](https://github.com/23002248/Word-Count/assets/151701774/314f81ff-4b01-4bba-94b1-887ca47621b8)
![image](https://github.com/23002248/Word-Count/assets/151701774/6cf5905c-e4aa-42bf-ba7b-42256f3fcf2b)




## RESULT:
Thus the program is written to find the word count from a text.
