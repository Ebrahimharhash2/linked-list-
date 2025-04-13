# 📌 Singly Linked List Implementation in C++
 
A complete and efficient implementation of a Singly Linked List with various operations, including insertion, deletion, traversal, reversal, cycle detection, and partitioning. Ideal for learning data structures, interview preparation, and low-level memory management in C++.

# 🚀 Features
✔ Core Operations

append() – Add node at the end.

prepend() – Add node at the beginning.

insert() – Insert node at a given index.

deleteFirst(), deleteLast(), deleteNode() – Remove nodes.

# ✔ Advanced Algorithms

reverse() – Reverse the list in-place.

findMiddleNode() – Floyd’s Tortoise & Hare (optimal middle node detection).

hasLoop() – Cycle detection using Floyd’s Algorithm.

partitionList(x) – Rearranges nodes so values < x come before ≥ x.

# ✔ Utility Functions

get(), set() – Access/modify node values.

printList() – Display the entire list.

Automatic memory management (destructor prevents leaks).

# 📌 Code Example
cpp
Copy
linkedlist myList(2);
myList.append(3);
myList.prepend(1);
myList.insert(2, 7);
myList.printList(); // Output: 1 → 2 → 7 → 3
myList.reverse();
myList.printList(); // Output: 3 → 7 → 2 → 1 

#  🔧 How to Use
Clone the repo:

bash
Copy
git clone https://github.com/yourusername/linked-list-cpp.git
Compile & Run (using g++):

bash
Copy
g++ main.cpp -o linkedlist
./linkedlist



 # 📊 Why This Project?
Learn Data Structures: Understand linked lists, pointers, and dynamic memory.

Interview Prep: Common questions (reversal, cycles, partitioning) are implemented.

Optimized Algorithms: Uses O(1) space for reversal and O(n) time for middle node detection.

# 📜 License
This project is open-source under the MIT License.

💬 Let’s Connect!
Got feedback? Want to collaborate?
🔗 LinkedIn: www.linkedin.com/in/
ebrahim-harhash-116955270

📧 Email: ebrahim.2367zzza@gmail.com

# 🎯 Key Takeaways
✅ Memory-safe (no leaks).
✅ Modular & Readable (easy to extend).
✅ Interview-Ready (covers common linked list problems).

⭐ Star the repo if you find it useful!

