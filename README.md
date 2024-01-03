# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: create a function fot the following operation

### Step 2: prompt the user to enter the two files one is sourse file another one is storage file
 
### Step 3: inside the functin  open the sourse file and copy the content in a variable 

### Step 4: next open the empty file 

### Step 5: then store it in the empty file

### Step 6: finally read the file and print it 

## PROGRAM:
~~~
# Python program for copying the contants from one to another 
# Developed by : Panduru somu
# Reference number : 212223240111
def function (file1,file2):   
   with open(file1,'r') as san:
          contant=san.read()
   with open(file2,'a+') as copy:
                 copy.write(contant)
                 copy.seek(0)
                 print(copy.read())
print("Enter a source file you want to copy : ",end='')
x= input()
print("enter a file you to store the data : ",end='')
y=input()
function(x,y)
~~~

### OUTPUT:
![WhatsApp Image 2024-01-03 at 07 32 13_e568a3f6](https://github.com/Pandurusomu/copy-file/assets/148988619/4b3d39ee-ea92-4b7f-9242-de4ee5366e2e)







## RESULT:
Thus the program is written to copy the contents from one file to another file.
