# Merge Sort
```
[22,27,16,2,18,6] -> Merge 
```

>_Write the stages of the above sequence according to the sort type._

```
                          [22,27,16,2,18,6]
                          /               \  
                         /                 \             
                [22,27,16]                 [2,18,6]
                /        \                /        \
               /          \              /          \
        [22,27]           [16]         [2,18]        [6]
        /     \             |           /  \          |
       /       \            |          /    \         |  
    [22]       [27]       [16]       [2]    [18]     [6]
       \        /           |          \     /        |   
        \      /            |           \   /         |  
        [22,27]            [16]         [2,18]       [6]  
              \            /              \          /
               \          /                \        /
                [16,22,26]                  [2,6,18]
                        \                   /
                         \                 /
                          [22,27,16,2,18,6]
```
_As above Sort the array by separating the elements of the array and then sorting them again._

## Big O : O(6*(log6))