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
```
Developed By: Sivaramakrishnan B
Register Number: 212222110044
```
## I) To find the maximum of marks using the list method sort.
```
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large  
```

## II) To find the maximum marks using the list method max().
```
def max_marks(marks):
   large = max(marks)
   return large
```

## III) To find the maximum marks without using builtin functions.
```
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

### I) USING LIST METHOD SORT: 
![214597273-4967a4d6-ba8e-4a08-9b28-ff836b2c6bfc](https://github.com/SivaramakrishnanBaskar/FindMaximum/assets/119476322/b384a7ca-f6a1-4e9b-9bcb-ae73fe92d40a)

### II) USING LIST METHOD MAX:
![214597442-8011ae4c-1f8f-4fb3-aa69-5c5f1b89f4d6](https://github.com/SivaramakrishnanBaskar/FindMaximum/assets/119476322/e2bb721e-4af1-4343-a4b8-6794bd9ae2ce)

### III) USING BUILT-IN FUNCTION:
![214597574-be6a5750-03d9-438f-9c84-2d7702b065e7](https://github.com/SivaramakrishnanBaskar/FindMaximum/assets/119476322/3c47cdd6-a46b-4d12-88ab-f5fc8e5791b7)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
