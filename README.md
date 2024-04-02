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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max


```
## Output:
![6 exp 1](https://github.com/Hemanath08/FindMaximum/assets/151807176/f04095f3-fa7d-4b60-ba45-b51f4b2ae6ca)
![6 exp 2](https://github.com/Hemanath08/FindMaximum/assets/151807176/734c188c-8675-4e73-9bcf-fae4f4d1f73c)
![6 exp 3](https://github.com/Hemanath08/FindMaximum/assets/151807176/c7127b9a-caba-4d58-9e8c-a0cdcde098f5)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
