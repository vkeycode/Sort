
# Insertion Sort
## Order of Operations
_First, it finds the smallest number of the array and replaces it with the first index, and the same process is applied to the following indexes._
``` 
First Array [22,27,16,2,18,6] 

1.Step      [2,27,16,22,18,6]

2.Step      [2,6,16,22,18,27]

3.Step      [2,6,16,18,22,27] 

Big O = O(n^2)

```

## Time Complexity

 _Which case does the number 18 fall into after the array is sorted?_

|  Best Case | Avarage Case  | Worst Case  |
| --|:-------:| -----:|
| [2,6] | [16,18] | [22,27]  |

_According to this table 18 in Avarage Case_

### [7,3,5,8,2,9,4,15,6] Write the first 4 steps of the array according to the Insertion Sort.

```
1.Step  [2,3,5,8,7,9,4,15,6]

2.Step  [2,3,4,8,7,9,5,15,6]

3.Step  [2,3,4,5,7,9,8,15,6]

4.Step  [2,3,4,5,6,9,8,15,7]
```