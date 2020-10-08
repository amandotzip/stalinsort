# stalinsort
Demonstrates a Stalin sort. Stay in line comrade.

# Algorithm Explained
The Stalin Sort is an incredibly destructive yet effective algorithm if you care not for the data you are sorting.

Say you have the list:
```
4 2 3 5 8
```
And we want to sort ascending. 4 is greater than 2, so instead of swapping the values like lesser algorithms, we delete the offending value ahead of the value we are currently observing. So we will delete 2, giving:
```
4 3 5 8
```
Continuing iteration:
```
4 5 8
```
The list is now in order :)
