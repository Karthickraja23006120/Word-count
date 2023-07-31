# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open a text file

### Step 2: 
read the opened text file

### Step 3: 
assign 0 in  count 
### Step 4:
split the opened text file in a for loop and add +1 in the count for every loop

### Step 5:
print the count value

### Step 6: 
end the program

## PROGRAM:
```
f=open("raja.txt",'r')
m=f.read()
count=0
for i in m.split():
     count+=1
print(count)
f.close()
```

### OUTPUT:
![output](/Screenshot%202023-07-25%20134323.png)
![output](/Screenshot%202023-07-31%20192613.png)
![output](/Screenshot%202023-07-31%20192709.png)


## RESULT:
Thus the program is written to find the word count from a text.
