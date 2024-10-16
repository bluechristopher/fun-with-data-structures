# Let's have fun with data structures

## Arrays
- An array is a data structure that stores a collection of elements of the same data type in a contiguous block of memory.
- Each element can be accessed using an index, indicating its position in the array.
- Enables direct access of elements through their index.


## Linked List
- A linked list is a linear data structure where nodes are stored as separate objects and linked together using pointers.
- Each node contains two parts: data and reference to the next node.
- Allows for dynamic memory allocation and efficient insertions and deletions, as nodes can be easily added or removed without reorganising the entire structure.


## Stack
- Collection of elements that follows the Last In First Out (LIFO) priniciple.
- Primary operations:
  * push (add element to top of stack)
  * pull (remove element from top of stack)
- Applications:
  * management of function calls
  * undo mechanisms in programs
    
## Linear Queue
- Linear data structure that follows the First In First Out (FIFO) principle.
- First element that is added to the queue is also the first one removed from queue.
- Primary operations:
  * enqueue (add element to rear)
  * dequeue (remove element from front)
- Applications of queues:
  * managing print jobs
  * handling events like user interactions with applications
  * managing incoming calls at call centres
 
## Circular Queue
- A variation where the last position is connected to the first position to form a circle.
- Utilises space more efficiently by allowing continuous addition and removal of elements without needing to shift elements.
  
## Hash Tables
- Allows for efficient data retrieval using keys
- Uses a hash function to compute an index into an array of buckets or slots, from which the desired value can be found.
- Average-case O(1) time complexity for search, insert, and delete operations.
- Applications:
  * database indexing
  * caching in web browsers
  * implementation of dictionaries and sets in python
  
## Binary Search Trees
- A hierarchical data structure in which each node has at most two children referred to as the left child and right child.
- For any given node, all elements in its left subtree are less than the node's value, and all elements in its right subtree are greater.
- Enables efficient searching, insertion, and deletion operations with average time complexity of O(log n).
- Applications:
  * autocompletion features
