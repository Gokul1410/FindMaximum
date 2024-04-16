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
Developed by: Gokul C
Register Number: 212223240040
'''

def max_marks(array):
    array.sort()
    return array[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
'''
Program to find the maximum of marks using the list method sort
Developed by: Gokul C
Register Number: 212223240040
'''

def max_marks(array):
 return max(array)  


```

iii) # To find the maximum marks without using builtin functions.
```Python
'''
Program to find the maximum marks without using builtin functions
Developed by: Gokul C
Register Number: 212223240040
'''

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1

```



## Output:
![Screenshot 2024-04-16 170759](https://github.com/Gokul1410/FindMaximum/assets/153058321/d4f64879-5d70-4705-b92c-e4710adf0b33)
![Screenshot 2024-04-16 170814](https://github.com/Gokul1410/FindMaximum/assets/153058321/2d879a34-4b83-4f12-af6a-56bd93ee38f4)
![Screenshot 2024-04-16 170827](https://github.com/Gokul1410/FindMaximum/assets/153058321/bba70493-9e6f-41ed-9e10-1e8c078a9793)
![Screenshot 2024-04-16 170837](https://github.com/Gokul1410/FindMaximum/assets/153058321/4a5ee1b3-fe6b-47ff-bfc4-6496b4852d24)
![Screenshot 2024-04-16 170851](https://github.com/Gokul1410/FindMaximum/assets/153058321/4a43c06b-38ae-4b40-b45a-3acd90873fff)
![Screenshot 2024-04-16 170904](https://github.com/Gokul1410/FindMaximum/assets/153058321/f8aa1913-2974-40a3-aaaf-e6eae47c734c)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
