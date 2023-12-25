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
#Program to find the word count.
#Developed by: Tirupathi Jayadeep
#RegisterNumber:23004426
num_word=0
with open ("sample.txt",'r') as f:
for i in f:
word=i.split()
num_word+=len(word)
print("number of words ={}".format(num_word)
### OUTPUT:
![Screenshot 2023-12-25 114417](https://github.com/23004426/Word-count/assets/144979327/cb28f3fb-a248-4d06-9ecf-7687ca6429a8)

![Screenshot 2023-12-25 114427](https://github.com/23004426/Word-count/assets/144979327/b5f78b21-b86c-4069-914f-1a4f63ae54d4)




## RESULT:
Thus the program is written to find the word count from a text.
