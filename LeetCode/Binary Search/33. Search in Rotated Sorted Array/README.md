### Approach To Solve

- Note store size of array somewhere as it may confuse you.

- first for the given sorted , rotated array using the find pivot index algorithm : find the pivot element (lowest value) index .
- then break the array in two parts using this pivot element and applay binary search individually to parts.

- if(target>=arr[pivot] and target<=arr[n-1]) ---> then apply binary search from (start=pivot) and (end=n-1)  
- else binary search from (start=0) and (end=pivot-1)

- also for target not found binary search will return -1.