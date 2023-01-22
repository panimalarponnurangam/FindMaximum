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
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: panimalar.p
RegisterNumber: 22009107
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: panimalar.p
RegisterNumber: 22009107
'''
def max_marks(marks):
    large = max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:panimalar.p 
RegisterNumber: 22009107
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot  ](https://user-images.githubusercontent.com/121490826/213915591-d182ae98-3794-4660-b8d7-c05c82b349d2.png)
![Screenshot ](https://user-images.githubusercontent.com/121490826/213915882-132603cf-6b11-4c69-b9a0-a0248afb34b8.png)
:![Screenshot ](https://user-images.githubusercontent.com/121490826/213915893-072f4f75-53d0-46a0-a868-3bc419031ad6.png)
## Result
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
