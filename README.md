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
Program to mark the maximum of marks using the list method sort
Developed by: ANANDHAMOORTHY.K
RegisterNumber: 212222100004

def max_marks(marks):
    marks.sort()
    b=marks[-1]
    return b
```

ii) # To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by:ANANDHAMOORTHY.K 
RegisterNumber: 212222100004
def max_marks(marks):
    a=max(marks)
    return a
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by:ANANDHAMOORTHY.K
RegisterNumber: 212222100004
def max_marks(list1):
    for i in list1:
        if i>94:
            return i
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)	# To find the maximum of marks using the list method sort.
![Screenshot 2023-06-08 111221](https://github.com/AnandhamoorthyKarthikeyan/FindMaximum/assets/119475998/31b71ac2-1ba7-497c-9d63-4a6866c10344)

ii) # To find the maximum marks using the list method max().
![Screenshot 2023-06-08 111238](https://github.com/AnandhamoorthyKarthikeyan/FindMaximum/assets/119475998/ea3ff1b2-fb17-4759-b6d8-48ede54299bc)

iii) # To find the maximum marks without using builtin functions.
![Screenshot 2023-06-08 111256](https://github.com/AnandhamoorthyKarthikeyan/FindMaximum/assets/119475998/47d4b628-647f-4b20-a41e-e9b9c8458512)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
