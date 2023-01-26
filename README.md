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
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the new file.
### Step 6: 
End the program.
## PROGRAM:
```python
#DEVELOPED BY:MOHAMED FAREED.F
#REGISTER NO: 22001617
with open("file2.txt") as fp:
    with open("file3.txt","w") as fp1:
        line= fp.read()
        fp1.write(line)
```
### OUTPUT:
![Screenshot from 2023-01-26 11-15-52](https://user-images.githubusercontent.com/121412904/214803502-4297860b-668e-4b8a-837b-4dbf9148dbd4.png)


![Screenshot from 2023-01-26 11-15-30](https://user-images.githubusercontent.com/121412904/214803826-c1b37fbf-3649-449f-ab6f-b62fcdb2bad9.png)


![Screenshot from 2023-01-26 11-15-19](https://user-images.githubusercontent.com/121412904/214803550-30cb52e7-a312-4e8f-8d10-1e292a3c2d0d.png)
-89da-4d58a830edba.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
