# DATE:
# EXP.NO:06
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
Python
```
def max_marks(array):
    array.sort()
    return array[-1]


```

ii)	# To find the maximum marks using the list method max().
Python
```
def max_marks(array):
    return max(array)


```

iii) # To find the maximum marks without using builtin functions.
Python
```
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1



```



## Output:
![image](https://github.com/user-attachments/assets/d5513c98-528d-46bb-b452-a5956f1e1ed2)

![image](https://github.com/user-attachments/assets/e4d3b2fb-97cf-4c27-a3a3-7318d6dad6b1)

![image](https://github.com/user-attachments/assets/57d43e87-b416-441a-b530-c8826e14ca49)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
