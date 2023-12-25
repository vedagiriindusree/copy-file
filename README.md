 # copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
Developed By:vedagiri Indu sree
Register No: 212223230236

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)

### OUTPUT:
![image](https://github.com/vedagiriindusree/copy-file/assets/149366776/66449ade-6b4f-4240-9981-49767c30b26d)
![image](https://github.com/vedagiriindusree/copy-file/assets/149366776/cf8df149-342a-46a5-a3b5-f2f7c75b0c04)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
