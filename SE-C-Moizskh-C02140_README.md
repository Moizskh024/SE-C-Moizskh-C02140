# 📚 Data Structures and Algorithms — C Practicals

A collection of **Data Structures and Algorithms (DSA) practical programs written in C** as part of my Second Year Computer Engineering coursework.

This repository contains practical implementations of fundamental data structures and algorithms, along with simple real-world-inspired applications to understand how these concepts work.

---

## 📌 About This Repository

The programs in this repository cover:

- Arrays and array operations
- Searching algorithms
- Bubble Sort
- Singly Linked Lists
- Stack-based browser navigation
- Queue-based patient registration
- Binary Search Trees
- Graph representation and traversal
- Hash tables and collision handling

Each practical focuses on applying a data structure or algorithm to solve a specific problem.

---

## 📚 Practicals and Assignments

### 1. Student Marks Management System using Arrays

**File:** `01_arrayoperations_marks.c`

A menu-driven program to manage student marks using an array.

**Operations:**
- Insert marks of students.
- Display all stored marks.
- Delete a mark from a specified position.
- Sort marks using Bubble Sort.
- Search for a mark using Linear Search.
- Search for a mark using Binary Search.
- Exit the program.

**Concepts:** Arrays, insertion, deletion, traversal, Bubble Sort, Linear Search, Binary Search.

---

### 2. Student Roll Number Sorting using Bubble Sort

**File:** `02_BStudentmarks.c`

A program that accepts student roll numbers and arranges them in ascending order using Bubble Sort.

**Operations:**
- Accept the number of students.
- Input each student's roll number.
- Sort roll numbers using Bubble Sort.
- Display the array after each sorting pass.
- Display the final sorted roll numbers.

**Concepts:** Arrays, comparison-based sorting, swapping, Bubble Sort, sorting passes.

---

### 3. Contact Management System using Singly Linked List

**File:** `03_LLcontactsys.c`

A basic contact management program implemented using a Singly Linked List. Each contact stores a name and phone number.

**Operations:**
- Insert a contact at the beginning.
- Insert a contact at the end.
- Delete a contact by name.
- Search for a contact.
- Display the contact list.

**Concepts:** Singly Linked List, nodes, pointers, dynamic memory allocation, insertion, deletion, searching, traversal.

---

### 4. Browser Navigation System using Two Stacks

**File:** `04_browsernavigationsystem.c`

A console-based simulation of browser navigation using two stacks to manage previously visited and forward pages.

**Operations:**
- Visit a new webpage.
- Navigate to the previous webpage using Back.
- Move to the next webpage using Forward.
- Display the current webpage.
- Exit the program.

The Back and Forward stacks demonstrate how browser navigation history can be managed.

**Concepts:** Stack, LIFO (Last In, First Out), push, pop, stack operations, browser history.

---

### 5. Hospital Patient Registration System using Queue

**File:** `05_patientregistrationsystem.c`

A patient registration simulation in which patients are added to a queue and attended in their order of arrival.

**Operations:**
- Add a patient to the queue.
- Attend the patient at the front of the queue.
- View all waiting patients.
- Check whether patients are waiting.
- Handle the queue-full condition.

**Concepts:** Queue, FIFO (First In, First Out), enqueue, dequeue, front, rear, queue overflow and underflow conditions.

---

### 6. Binary Search Tree Operations

**File:** `06_BSToperations.c`

A Binary Search Tree (BST) program that stores student roll numbers and supports common BST operations.

**Operations:**
- Insert a student roll number.
- Search for a roll number.
- Delete a student record using its roll number.
- Find the minimum node in a subtree.
- Display the tree using:
  - Inorder Traversal
  - Preorder Traversal
  - Postorder Traversal

**Concepts:** Binary Search Tree, tree nodes, pointers, recursion, insertion, deletion, searching, tree traversal.

---

### 7. Social Media Network using Graph

**File:** `07_socialmedianetworking.c`

A simple social network model represented using a graph. Users are represented as vertices, and connections between users are represented as edges.

**Operations and implementation:**
- Represent connections using an adjacency matrix.
- Add a connection between two users.
- Traverse the network using Breadth First Search (BFS).
- Traverse the network using Depth First Search (DFS).

**Concepts:** Graph, vertices, edges, adjacency matrix, graph traversal, BFS, DFS, visited array.

---

### 8. Library Book Management using Hashing

**File:** `08_librarybookmanagement.c`

A library book indexing program that stores and searches book IDs using a hash table.

**Operations:**
- Initialize the hash table.
- Calculate an index using a hash function.
- Insert book IDs into the hash table.
- Handle collisions using Linear Probing.
- Search for a book ID.
- Display the hash table.

**Concepts:** Hashing, hash function, hash table, collision handling, open addressing, Linear Probing.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| C | Programming language used for the practicals |
| GCC | C compiler |
| Visual Studio Code | Code editor / development environment |
| Git | Version control |
| GitHub | Source code hosting and repository management |

---

## 📂 Repository Structure

```text
SE-C-Moizskh-C02140/
│
├── 01_arrayoperations_marks.c
├── 02_BStudentmarks.c
├── 03_LLcontactsys.c
├── 04_browsernavigationsystem.c
├── 05_patientregistrationsystem.c
├── 06_BSToperations.c
├── 07_socialmedianetworking.c
└── 08_librarybookmanagement.c
```

The repository currently contains eight C source files. Each file is a separate practical program with its own `main()` function where applicable, so compile and run the required practical individually.

---

## ▶️ How to Compile and Run

### Requirements

- GCC compiler installed on your system.
- A terminal or command prompt.
- Visual Studio Code (optional).

### Compile a practical

Open a terminal in the repository folder and compile the required `.c` file.

**Example — Student Marks Management:**

```bash
gcc 01_arrayoperations_marks.c -o array_marks
```

### Run the program

**Windows PowerShell:**

```powershell
.\array_marks.exe
```

**Linux / macOS:**

```bash
./array_marks
```

### Compile another practical

Replace the source filename and output name with the practical you want to execute.

For example:

```bash
gcc 06_BSToperations.c -o bst_operations
```

Then run the generated executable using the command appropriate for your operating system.

---

## 🧠 Data Structures and Algorithms Covered

| No. | Data Structure / Algorithm | Practical Application |
|---:|---|---|
| 1 | Array | Student Marks Management |
| 2 | Bubble Sort | Student Roll Number Sorting |
| 3 | Singly Linked List | Contact Management |
| 4 | Stack | Browser Navigation |
| 5 | Queue | Hospital Patient Registration |
| 6 | Binary Search Tree | Student Roll Number Operations |
| 7 | Graph, BFS and DFS | Social Media Network |
| 8 | Hash Table, Linear Probing | Library Book Management |

---

## 🎯 Learning Objectives

Through these practical assignments, I aim to understand and implement:

- Fundamental data structures and their operations.
- Array insertion, deletion, traversal, searching, and sorting.
- Linear Search and Binary Search.
- Bubble Sort and its intermediate passes.
- Linked list creation and manipulation using pointers.
- Dynamic memory allocation.
- Stack operations and LIFO behaviour.
- Queue operations and FIFO behaviour.
- Binary Search Tree insertion, deletion, searching, and traversal.
- Graph representation using an adjacency matrix.
- Graph traversal using BFS and DFS.
- Hash functions and collision resolution using Linear Probing.
- Modular programming and problem-solving in C.

---

## 📌 Notes

- All programs are written in C.
- Each practical should be compiled separately.
- The programs are intended for learning and academic demonstration.
- Input and output are handled through the console.

---

**Repository:** SE-C-Moizskh-C02140  
**Subject:** Data Structures and Algorithms  
**Language:** C  
**Compiler:** GCC
