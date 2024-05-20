# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the file you want read

### Step 2: 
Open the file in read mode
 
### Step 3: 
Use the built in function copy()

### Step 4: 
Write the copied file

### Step 5: 
The File is read and copied.

### Step 6: 
End the program

## PROGRAM:
```
#Developed by: Vikaash P
#Register Number: 212223240180

with open("text1.txt",'r') as file:
    msg=file.read()
with open("copy.txt","w") as file2:
    file2.write(msg)
```

### OUTPUT:
![image](https://github.com/Vikaash16/Copy-File/assets/139218414/7deedf72-970b-4220-a182-0175125f22c2)

![image](https://github.com/Vikaash16/Copy-File/assets/139218414/7c041076-24cf-4744-8c14-01a75ed67315)






## RESULT:
Thus the program is written to copy the contents from one file to another file.
