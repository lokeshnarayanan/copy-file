# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Create a text3.txt with some content in it

### Step 2: Open the text3.txt file in read mode
 
### Step 3: Create a copy1.txt file using write mode

### Step 4:  Copy the content of text3.txt file to copy1.txt using write function

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Programmed By: Lokesh N
RegisterNumber: 212222100023
'''
with open("text3.txt",'r') as fp:
    msg1=fp.read()
with open("copy1.txt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/lokeshnarayanan/copy-file/assets/119393019/4bd563b0-e34e-40e5-ab91-988ee8c6bf9a)
![image](https://github.com/lokeshnarayanan/copy-file/assets/119393019/40c354cb-41c8-49b2-8db3-0c462d52aebd)
![image](https://github.com/lokeshnarayanan/copy-file/assets/119393019/db538f09-44f0-480f-b687-30baf503ce1f)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
