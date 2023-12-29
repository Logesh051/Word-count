# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program.

### Step 2:
Give the input string.

### Step 3:
Print the original string.

### Step 4:
using len(test_string.split()) get the result.

### Step 5:
Print the word count.

### Step 6:
End the program.

## PROGRAM:
#python program for word count
#Developed by : Logesh.N.A
#Reference no : 23012242

def wordcount(filename):
count=0
with open(filename,"r") as f:
for data in f:
words=data.split()
for word in words:
count+=1
print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
```

### OUTPUT:
![Screenshot 2023-12-29 233553](https://github.com/Logesh051/Word-count/assets/144979188/9d3faf3e-fb05-4e1a-b65d-949709860374)

![Screenshot 2023-12-29 233614](https://github.com/Logesh051/Word-count/assets/144979188/24576299-960b-4b37-a016-16ed13012d4e)


## RESULT:
Thus the program is written to find the word count from a text.
