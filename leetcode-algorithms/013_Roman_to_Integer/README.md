首先建立一个map 本题中用的是unordered_map，它内部用的是哈希表，而map用的是红黑树，相比起来unordered_map更适合于查找，能够达到O（1）的时间复杂度，而map的查找则是O（logn）。但是map是有序的，而unordered_map的内部存储则是无序的。但是构建一个map空间占用会比较大