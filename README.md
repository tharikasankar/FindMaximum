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
Developed by: THARIKA S
RegisterNumber: 212222230159
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by: THARIKA S
RegisterNumber: 212222230159
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed by: THARIKA S
RegisterNumber: 212222230159
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max=i
    return max




```
## Sample Input and Output
![output](./img/max_marks1.jpg)  

## Output:
![image](https://github.com/tharikasankar/FindMaximum/assets/119475507/b9d70f7d-1be3-4e4f-b35a-5915a9a874b0)
![image](https://github.com/tharikasankar/FindMaximum/assets/119475507/2dd87f31-7a4b-4d0c-b9ee-37433de085b3)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
