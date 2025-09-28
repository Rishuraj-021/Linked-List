# Linked-List
## 🧭 Aim:
 To understand and implement a Linked List in C++, a dynamic data structure that allows efficient insertion and deletion of elements without reallocating or reorganizing the entire structure.

## 🔍 Theory:
A linked list is a linear data structure composed of nodes, where each node contains two parts:
- Data – the actual value stored.
- Pointer – a reference to the next node in the sequence.
Linked lists are dynamic in nature, meaning they can adjust their size during execution. This makes them more memory-efficient than arrays in scenarios where the number of elements is not known in advance.
🔗 Types of Linked Lists
- Singly Linked List: Each node points to the next node. Traversal is one-directional.
- Doubly Linked List: Each node contains two pointers—one to the next node and one to the previous node. Allows bidirectional traversal.
- Circular Linked List: The last node points back to the first node, forming a loop.

### 📐 Characteristics:
- Dynamic Size: Can grow or shrink at runtime.
- Efficient Insertions/Deletions: Especially at the beginning or middle.
- No Random Access: Unlike arrays, accessing an element requires traversal from the head.
## 🧮 Algorithm (Singly Linked List Operations):
1. Insertion at Beginning
- Create a new node.
- Set its pointer to the current head.
- Update head to the new node.
2. Insertion at End
- Create a new node.
- Traverse to the last node.
- Set the last node’s pointer to the new node.
3. Deletion by Value
- Traverse the list to find the node with the given value.
- Update the previous node’s pointer to skip the deleted node.
- Free the memory of the deleted node.
4. Traversal
- Start from the head.
- Visit each node and process its data.
- Move to the next node until the end is reached.
5. Search
- Start from the head.
- Compare each node’s data with the target.
- Return success if found, else continue until the end.

## 🧪 Applications:
- Implementing stacks and queues.
- Dynamic memory allocation.
- Graph adjacency representation.
- Real-time systems where memory usage must be optimized.

## ✅ Conclusion:
Linked lists are a foundational concept in data structures, offering flexibility and efficiency in managing collections of data. Their dynamic nature makes them suitable for applications where memory usage and performance are critical. Understanding linked lists is essential for mastering more advanced structures like trees, graphs, and hash tables.
