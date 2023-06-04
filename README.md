# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Create a file object and get file name from the user

Step 2:
Open the file given by the user

Step 3:
Using for loop acess the file

Step 4:
Use split funtion to separate the words

Step 5:
The words is then counted by len function

Step 6:
Print the number of words
## PROGRAM:
```
'''
Program to count the number of words in a file
Developed by: PERARASU M
Register Number: 212222100057
'''
fp=input("Enter the file name:")
words=0
with open(fp,'r') as f:
  for line in f:
    word=line.split()
    words+=len(word)
print("Number of words:",words)
```
### OUTPUT:
![out1](https://github.com/PERARASU10/Word-count/assets/118348589/5715fa10-69e1-4b5a-a547-c62c55683102)

![out2](https://github.com/PERARASU10/Word-count/assets/118348589/99adcb67-28c1-4647-af23-b7696580c3c2)



## RESULT:
Thus the program is written to find the word count from a text.
