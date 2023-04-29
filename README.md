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
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-04-29 at 11-14-30 Exp 3a-CR- Maximum of a list of numbers Attempt review](https://user-images.githubusercontent.com/118343461/235286070-f690e70a-41aa-494a-9dc5-1d529dde119d.png)
## Output:
![Screenshot 2023-04-29 at 11-15-02 Exp 3a-CR- Maximum of a list of numbers Attempt review](https://user-images.githubusercontent.com/118343461/235286141-b2a1aef8-3e8b-48b3-8c36-1038de580e53.png)
## Output:
![Screenshot 2023-04-29 at 11-15-23 Exp 3a-CR- Maximum of a list of numbers Attempt review](https://user-images.githubusercontent.com/118343461/235286150-cebbe8d3-f460-470f-9365-671658018c34.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
