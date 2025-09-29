📌 **Experiment 19: Stack Implementation**

**🎯 Aim:**  
To implement a stack using arrays in C++ and perform basic operations such as push, pop, and display of stack elements.

**📖 Theory:**  
A **stack** is a linear data structure that follows the **LIFO (Last In, First Out)** principle, where the last element inserted is the first one to be removed.  
- **Top:** Points to the current top element of the stack.  

**🔹 Stack Operations:**  
1. **Push** – Insert an element at the top of the stack.  
2. **Pop** – Remove the top element from the stack.  
3. **Display** – Show all elements in the stack from top to bottom.  

This implementation uses a fixed-size array and checks for **overflow** (pushing into a full stack) and **underflow** (popping from an empty stack).

**⚙️ Algorithm:**  

**Push Operation:**  
1. Check if `top` is at maximum size. If yes, print "Stack Overflow".  
2. Increment `top` and insert the element at `arr[top]`.  

**Pop Operation:**  
1. Check if the stack is empty (`top = -1`). If yes, print "Stack Underflow".  
2. Print the element at `arr[top]` and decrement `top`.  

**Display Operation:**  
1. Check if the stack is empty. If yes, print "Stack is empty".  
2. Loop from `top` to `0` and print all elements.

**📝 Topics Covered:**  
- Stack data structure  
- Array implementation of stack  
- LIFO principle  
- Handling overflow and underflow  
- Class-based programming in C++  

**✅ Conclusion:**  
- Stack implemented successfully using arrays in C++.  
- Demonstrated push, pop, and display operations.  
- Overflow and underflow handled correctly.  
- Clear understanding of stack operations using classes in C++.
