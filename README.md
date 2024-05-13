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
#developed by : E Prasanth
#reg no: 212221233002
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
           max1=array[i]
    return max1
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark


```



## Output:
![Screenshot (5)](https://github.com/PrasanthE2001/FindMaximum/assets/114572171/e1f6f6ce-0e3a-4a4f-8cbe-c0a8224a16c5)
![Screenshot (27)](https://github.com/PrasanthE2001/FindMaximum/assets/114572171/5c660dc1-e62f-4d95-9d52-03c8edeff85c)
![Screenshot (6)](https://github.com/PrasanthE2001/FindMaximum/assets/114572171/ab691f85-b6e6-497f-a9b7-eaf4c35b4951)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
