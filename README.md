# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.
### Step 2: 
Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.

### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.

## PROGRAM:
```
Developed by:E.PRIYADHARSHINI.E
Register Number:23012593
num=0
with open("sample.txt",'r') as f:
    for i in f:
        words=i.split()
        for word in words:
        num+=len(word)
print("The num of words in the text file is:",num)
```

### OUTPUT:

<img width="308" alt="image" src="https://github.com/EPriyadharshini/Word-count/assets/144870831/bd29bfa9-5986-412f-8679-704ceb76ec96">


## RESULT:
Thus the program is written to find the word count from a text.
