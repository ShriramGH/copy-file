# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
Read the file and store in a variable.
 
### Step 3:
Now create a new file in which we want to paste the content using write access mode.

### Step 4:
Use write function to copy the read file that has been stored in the variable

### Step 5: 
The content in the original file will be copied in the new file.

### Step 6: 
End the program.

## PROGRAM:
```

'''

Developed by:Shriram s

Register Number:22008494

'''


with open('text.txt','r') as firstfile:

    with open('text2.txt','a') as secondfile:
    
        for line in firstfile:
        
            secondfile.write(line)

```

### OUTPUT:

![5c data1](https://user-images.githubusercontent.com/117991122/214781662-b37c871f-db80-4eb2-837e-d52bfb644da3.png)

![5c ram](https://user-images.githubusercontent.com/117991122/214781939-84556807-9383-4a7b-a5d2-46b35488d08d.png)

![5c output](https://user-images.githubusercontent.com/117991122/214781963-4337914f-8532-4b1f-80a8-d694fb560234.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
