# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i) #Selection sort

```

Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: MS Dharanish
RegisterNumber: 212223240027

def selection_sort(nums):
    for i in range(1,len(nums)):
        item_to_insert=nums[i]
        j=i-1
        while j>=0 and nums[j]>item_to_insert:
            nums[j+1]=nums[j]
            j-=1
        nums[j+1]=item_to_insert
list_of_nums = eval(input())
selection_sort(list_of_nums)
print(list_of_nums)




```
ii)	#Insertion Sort
```
 
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: MS Dharanish
RegisterNumber:212223240027 

def insertion_sort(nums):
    for i in range(1,len(nums)):
        item_to_insert=nums[i]
        j=i-1
        while j>=0 and nums[j]>item_to_insert:
            nums[j+1]=nums[j]
            j-=1
        nums[j+1]=item_to_insert
list_of_nums = eval(input())
insertion_sort(list_of_nums)
print(list_of_nums)






```

## Output:
i) #Selection sort




![Screenshot 2023-12-30 211943](https://github.com/MSDharanish-23011819/Sorting-Algorithm/assets/147139454/3e5ac3d0-8a48-41a5-b5a4-47b060ed9a9d)

ii)	#Insertion Sort



![Screenshot 2023-12-30 212230](https://github.com/MSDharanish-23011819/Sorting-Algorithm/assets/147139454/d5ed008d-2e95-4835-9887-27c18d290ae3)


## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
