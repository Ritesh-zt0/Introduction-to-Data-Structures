

* A data structure is a way to store and organize data in a computer, so that it can be used efficiently.

We talk about data-structures as:
1. Mathemtical/Logical models or Abstract data types: ADTs define data and operations, but no implementation. Different ADTs are Arrays, Linked List, Stack, Queue, Tree, Graph, etc.

     a.  List:
     - Collection of similar data types.
     - Store a given number of elements of any type.
     - Read elements by position.
     - Modify element at a position.
     - Empty list has size 0. We can insert, remove, count, read/modify element at a position.
          ![tttt](https://user-images.githubusercontent.com/93812163/235986171-59c31855-a6a3-43ae-956e-281f3f973217.png)
     
          Array:
          - Access - Read/write element at an index = Elements are arranged in one contiguous block of memory using the starting address or the base address of the block of the memory and the index or the position of the element, we can calculate the address of that particular element and access it in constant time. Big O notation that is used to describe the time complexity of operations for constant time complexity is written as O(1).
          - Insertion: Inserting a new element at the end will happen in constant time O(n) if the array is not full. If the array is full, then we will create a new copy array double the size of the previous array and then we copy the elemts of previous array into the new array.
          - We can access any elements at any index in constant time which is the property of the array but if we have to insert or remove any elements from the list it is costly. If the list grows and shrinks a lot we have to create new arrays and copy the elements from the previous array to the new array again and again.
          - Array implementation is not efficient in terms of memory.
     
     b. Linked List:
     - 

      
