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
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num
```
## Output:
![Screenshot 2024-03-23 151900](https://github.com/Narmadhasree48/FindMaximum/assets/144979451/07ecdfc1-cc28-4f39-a0c2-e6b44bf9ceeb)
![Screenshot 2024-03-23 151914](https://github.com/Narmadhasree48/FindMaximum/assets/144979451/6b8b6750-17f7-4676-bdde-47d5ebe0dc62)
![Screenshot 2024-03-23 151931](https://github.com/Narmadhasree48/FindMaximum/assets/144979451/e8e992d5-4020-48de-baa1-64130d9f9520)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
