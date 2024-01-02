# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file with.text extention
### Step 2: 
add some extention
### Step 3: 
create a python file
### Step 4:  
write a code the number of words in that file
### Step 5: 
run the program
### Step 6: 
display the output
## PROGRAM:
def program():
    count=0
    with open("text.txt","r")as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("total number of words:",count)
 program()
### OUTPUT:
![Screenshot 2024-01-02 143820](https://github.com/Harishragaventhira/Word-count/assets/145548269/02537ae3-464a-48a8-bf21-cfd0e8c4622e)
![image](https://github.com/Harishragaventhira/Word-count/assets/145548269/b64ea907-c171-4109-bf91-647f8a3be7f3)


## RESULT:
Thus the program is written to find the word count from a text.
