# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Naveenkanthan L
RegisterNumber: 23007705
'''
def max_marks(marks):
    marks.sort()
    return marks[len(marks)-1]

```

ii)	# To find the maximum marks using the list method max().
```

def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    list1.sort()
    return list1[len(list1)-1]
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
## Output:
#### 1st program
<img width="612" alt="290136933-10c17172-af89-4ffc-8e6f-b5042959a3c9" src="https://github.com/Naveen1825/FindMaximum/assets/138969868/197e48b7-1743-4bef-966a-43d4ebc993ef">

#### 2nd program
<img width="609" alt="290137018-66d8c195-42de-496e-849f-ee088637940c" src="https://github.com/Naveen1825/FindMaximum/assets/138969868/206a2dd9-e927-46a7-bea2-8bc3a297f0d1">

#### 3rd program
<img width="604" alt="290137111-5579400a-f9a9-4223-bc52-eca7562aec20" src="https://github.com/Naveen1825/FindMaximum/assets/138969868/2edfdaea-18d1-4c92-a43b-f12247c31f77">


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
