# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Open the first file in read mode
### Step 2:

Open the second file in append mode
### Step 3:

Every word in first file is copied to second file using write()
### Step 4:

close the first filepython program for copying the contents from one file to another file.
### Step 5:

close the second file

## PROGRAM:
Developed by: SARGURU K
RegisterNumber: 22002828

f1=open("sample1.txt","r")
f2=open("sample2.txt","a")
for line in f1:
    f2.write(line)
f1.close()
f2.close()

### OUTPUT:
![1](./sam1.png)

![2](./sam2.png)





## RESULT:
Thus the program is written to copy the contents from one file to another file.