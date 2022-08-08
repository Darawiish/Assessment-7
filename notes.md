Time results.

Results for the extraLargeArray
insert 1.2479574979999999 s
append 21.766761 ms

Results for the largeArray
insert 8.784641 ms
append 762.669 μs

Results for the mediumArray
insert 323.691 μs
append 266.713 μs

Results for the smallArray
insert 196.809 μs
append 215.266 μs

Results for the tinyArray
insert 399.965 μs
append 193.488 μs


4. The doublerAppend() uses the .push() method and the doublerInsert() uses the .unshift() method. The .push() method is O(1) and unshift is O(N)?The push is faster with better scaling as the array get bigger and bigger. This is because the .push method does not have to rearrange the original array and adds to the end of the array whereas the unshift will have to "shift" over the data in the array to add in front.

5. After the doing the research the following logic still holds true. Even after reversing the .push() it will 10ms faster than the .unshift() do the fact it's running through more steps by shifting the data points to the left to add at the 0 index. 