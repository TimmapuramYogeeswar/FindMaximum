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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    max=marks[0]
    for i in marks:
        if i > max:
            max=i
    return max
```



## Output:

![image](https://github.com/user-attachments/assets/e762184a-8d0e-41b1-ba7b-69403d2a8bb8)

![image](https://github.com/user-attachments/assets/70b39cbf-2197-4231-a193-0c5556832d5d)

![image](https://github.com/user-attachments/assets/04e295d6-e8eb-4733-87c6-353d73d9c889)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
