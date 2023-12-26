# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file

### Step 2: 
Open the required file by using the function "with".

### Step 3: 
Then use the laptop to assign the i value in the file.

### Step 4: 
Using split function to spilt the words 

### Step 5: 
Finding the given length of the words by using len() fuction.

### Step 6: 
Calling the function and Printing the number of words.

## PROGRAM:
```
#program to count number of words
#Developed by:R.SANJANA
#Register Number:23008112

count=0
with open("anthro.txt",'r') as f:
    for data in f:
        words=data.split()
        for word in words:
            count+=1
print("Total words:",count)
```

### OUTPUT:
![Screenshot 2023-12-26 070450](https://github.com/23008112/Word-count/assets/138972470/a59b422c-39f1-493f-b1ee-793f961e86cc)

![Screenshot 2023-12-26 070416](https://github.com/23008112/Word-count/assets/138972470/7757e63b-f8e9-48f8-8429-ab1d52046c12)

## RESULT:
Thus the program is written to find the word count from a text.
