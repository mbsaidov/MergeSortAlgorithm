# MergeSortAlgorithm

>**1. [16,21,11,8,12,22]  --> Merge sort**
- Here, we see that an array of 6 items is divided into two arrays of size 3 and 3 respectively.
- Now, again find that is left index is less than the right index for both arrays, if found yes, then again calculate mid points for both the arrays.
                                    [16,21,11,8,12,22]
                                    
                              [16,21,11]              [8,12,22] 
                              
                             [16]  [21,11]           [8]  [12,22]
                             
                            [16]   [21] [11]        [8]   [12] [22]
                           
* After dividing the array into smallest units, start merging the elements again based on comparison of size of elements
* Firstly, compare the element for each list and then combine them into another list in a sorted manner.

                          [16]   [21] [11]          [8]   [12] [22]
                          
                           [16]   [11,21]            [8]   [12,22]  
                           
                             [11,16,21]                [8,12,22]
                             
* After the final merging, the list looks like this:

              [8,11,12,16,21,22]
              


**Big-O Notation**

> (nlogn) 
