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
# Program to mark the maximum of marks using the list method sort.
# Developed by: MANOJ M
# Register No:212223231022
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
# Program to find the maximum marks using the list method max().
# Developed by: MANOJ M
# Register No: 212223231022
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```
# Program to find the maximum marks without using builtin functions.
# Developed by:MANOJ M
# Register No: 212223231022
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark


```



## Output:
![image](https://github.com/Manoj0079940/FindMaximum/assets/149366208/ec1e8b20-6c32-4e34-b772-8a64dce80ea4)
![image](https://github.com/Manoj0079940/FindMaximum/assets/149366208/af18843f-8117-4900-b89c-2b3434e27d1a)
![image](https://github.com/Manoj0079940/FindMaximum/assets/149366208/330dda9b-c953-4e92-ace9-243fddd50eb4)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
