# Introduction to Data-Structures

* A data structure is a way to store and organize data in a computer, so that it can be used efficiently.

We talk about data-structures as:
1. Mathemtical/Logical models or Abstract data types: Abstract Data Types define data and operations, but no implementation. Different ADTs are List, Arrays, Linked List, Stack, Queue, Tree, Graph, etc.

     a.  List:
     - List is array based collection (ArrayList).
     - Collection of similar data types.
     - Store a given number of elements of any type.
     - Read elements by position.
     - Modify element at a position.
     - Empty list has size 0. We can insert, remove, count, read/modify elements at a position.
          ![tttt](https://user-images.githubusercontent.com/93812163/235986171-59c31855-a6a3-43ae-956e-281f3f973217.png)
     
      b. Array:
      - Read/write element at an index = Elements are arranged in one contiguous block of memory using the starting address or the base address of the block of the memory and the index or the position of the element, we can calculate the address of that particular element and access it in constant time. Big O notation that is used to describe the time complexity of operations for constant time complexity is written as O(1).
      - Insertion: Inserting a new element at the end will happen in constant time O(n) if the array is not full. If the array is full, then we will create a new copy array double the size of the previous array and then we copy the elements of previous array into the new array.
      - We can access any elements at any index in constant time which is the property of the array but if we have to insert or remove any elements from the list it is costly. If the list grows and shrinks a lot we have to create new arrays and copy the elements from the previous array to the new array again and again.
      - Array implementation is not efficient in terms of memory.
     
     c. Linked List:
     - LinkedList is node-pointer based collection (LinkedListNode).
     - Linked List is always identified by the address of the first node.
     - Each node stores the data as well as the link/points to the next node. First node is also called the head node, and the only information of the list which we keep all the time is address of the head/first node.
     - Address of the head/first node gives us access of the complete list.
     - Address of the last node is null or 0, which means that the last node doesn't point to any other node.
     - If we want to add anything to a linked list, we will create an independent node and assign this independent node's address to the previously last node address which contained null/0.
     - Unlike Arrays we cannot access any of the elements in a constant time in Linked List.
     - Time taken to access elements (T) is directly proportional to the size of the list (n), i.e, T ∝ n. Or in other words we can say that the time complexity of this operation is O(n).
     - Insertion will be a simple operation as we don't have to shift all the positions as we had to in Arrays. Time complexity = O(n).
     - Delete time complexity will also be O(n).
     - No extra use of memory because we create and delete nodes as and when needed.
     ![tttt](https://user-images.githubusercontent.com/93812163/236188922-0eabe460-332e-4fb7-9519-be19c55ca619.png)
     
       Array vs Linked List:
       
       > ![tttt](https://user-images.githubusercontent.com/93812163/236384558-dd0eaf29-5632-4c35-90a0-781528a9d66d.png)





      
