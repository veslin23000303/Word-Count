# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
Define a function which will count the word in the given file.
### Step 2:
Create a file pointer and open the file.
### Step 3:
Initialize word count as zero.
### Step 4:
For each line in file, split it into words and find number of the words in every line.
### Step 5:
Sum the number of words in each line.
### Step 6:
Display the total words in the file.
### Step 7:a
Close the file pointer and end the program. 

## PROGRAM:
```
Developed by: VESLIN ANISH A
Register no: 212223240175
```
```py
num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num) 
```
### OUTPUT:

![Screenshot 2024-05-23 155420](https://github.com/veslin23000303/Word-Count/assets/151148539/85d47d38-b1bd-411b-8c92-ffc5053ff566)



## RESULT:
Thus the program is written to find the word count from a text.
