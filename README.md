# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
##Step 1:
Decleare number of words is 0

##Step 2:
open it with txt file

##Step 3:
Give range for i

##Step 4:
Then nxt split the words

##Step 5:
count the number of words

##Step 6:
Giving print statement for getting output.
## PROGRAM:
```
 Program to count the no. of words in a file.
# Developed by Gokularamanan k
# Reg.no: 212222230040
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)     

```

### OUTPUT:
![word count 1](https://github.com/Gokulanbazhagan/Word-count/assets/119518996/1c7da5bd-6d47-4fb8-b5c3-03bbecb76c24)
![word count 2](https://github.com/Gokulanbazhagan/Word-count/assets/119518996/3b48dde4-cf83-4da6-9e00-27f0df90b149)




## RESULT:
Thus the program is written to find the word count from a text.
