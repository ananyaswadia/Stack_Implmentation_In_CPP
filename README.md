# Stack_Implmentation_In_CPP
## Aim
To implement stack data stucture in C++/
## Theory 
### What are stacks?
In C++, a stack is a container adapter provided by the Standard Template Library (STL) that implements a stack data structure. It operates on the Last-In, First-Out (LIFO) principle, meaning the last element added to the stack is the first one to be removed.

<img width="512" height="333" alt="image" src="https://github.com/user-attachments/assets/2509660c-9f0b-45f3-9220-0ba7944eb0c5" />



### Key Characteristics and Operations:
1. LIFO Principle: Elements are added and removed only from one end, referred to as the "top" of the stack.
2. push(): Adds an element to the top of the stack.
3. pop(): Removes the element from the top of the stack.
4. top(): Returns a reference to the element at the top of the stack without removing it.
5. empty(): Checks if the stack is empty, returning true if it is, and false otherwise.
6. size(): Returns the number of elements currently in the stack.

### Common Use Cases
Stacks are widely used in various programming scenarios, including:
Function Call Management

Expression Evaluation

Undo/Redo Functionality

Browser History

Syntax Parsing

### Basic Operations
1. Inserting Elements-In stack, new elements can only be inserted at the top of the stack by using push() method.
  
2. Accessing Elements-Only the top element of the stack can be accessed using top() method.

3. Deleting Elements-In stack, only the top element of the stack can be deleted by using pop() method in one operation.

4. empty()-This checks whether the stack is empty. It returns true if the stack has no elements; otherwise, it returns false.

5.  Size of stack-The size() function in a stack returns the number of elements currently in the stack. It helps to determine how many items are stored without modifying the stack.


## Algorithm
1. Initialize an empty stack.
2. Push 10 onto the stack.
3. Push 20 onto the stack.
4. Push 30 onto the stack.
5. Display all elements in the stack→ Output: 10 20 30
6. Retrieve and display the top element of the stack→ Output: 30
7. Pop the top element from the stack→ Element removed: 30
8. Display all elements in the stack→ Output: 10 20
9. Push 40 onto the stack.
10. Push 50 onto the stack.
11. Push 60 onto the stack.
12. Display all elements in the stack→ Output: 10 20 40 50 60

## Conclusion
We learnt to implement bsic operations on stacks.
