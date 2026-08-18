# OPERATING-SYSTEMS
Operating Systems Lab Manual containing programs, experiments, and practical implementations covered in the OS laboratory. This repository is intended for learning, practice, and easy reference for OS lab work.
# 🖥️ Operating Systems Lab — Complete Practical Repository

Welcome to the **Operating Systems Lab** repository! 🚀

This repository is a comprehensive collection of **Operating Systems laboratory programs, implementations, experiments, and study resources**. It is designed to provide a practical understanding of how operating-system concepts work behind the scenes—from **process creation and CPU scheduling to memory management, synchronization, deadlocks, file systems, and disk scheduling**.

The goal is not just to provide programs, but to create a **structured reference for understanding, implementing, testing, and revising core Operating Systems concepts**.

---

## 📚 Topics Covered

### 1. ⚙️ Process Management

Programs and experiments related to processes and process control.

* Process creation
* Parent and child processes
* `fork()`, `wait()`, and `exec()`
* Process states
* Process termination
* Inter-process communication (IPC)
* Pipes and related concepts

### 2. 🧠 CPU Scheduling

Implementation and comparison of different CPU scheduling algorithms.

* First Come First Serve (FCFS)
* Shortest Job First (SJF)
* Shortest Remaining Time First (SRTF)
* Priority Scheduling
* Round Robin (RR)
* Preemptive and Non-Preemptive Scheduling
* Waiting Time calculation
* Turnaround Time calculation
* Response Time calculation
* Average scheduling performance

### 3. 🔄 Process Synchronization

Programs demonstrating how multiple processes or threads coordinate access to shared resources.

* Critical Section Problem
* Race Conditions
* Mutual Exclusion
* Semaphores
* Mutex
* Producer–Consumer Problem
* Reader–Writer Problem
* Dining Philosophers Problem

### 4. 🔒 Deadlocks

Understanding and implementing techniques for preventing and avoiding deadlocks.

* Deadlock conditions
* Resource Allocation
* Deadlock Detection
* Deadlock Prevention
* Deadlock Avoidance
* Banker's Algorithm
* Safe and Unsafe States

### 5. 💾 Memory Management

Implementation of techniques used by operating systems to manage main memory.

* Contiguous Memory Allocation
* Fixed Partitioning
* Variable Partitioning
* First Fit
* Best Fit
* Worst Fit
* Internal Fragmentation
* External Fragmentation

### 6. 🧩 Page Replacement Algorithms

Simulation of virtual memory and page replacement techniques.

* FIFO
* Optimal Page Replacement
* LRU
* Page Fault Calculation
* Page Hit Calculation
* Comparison of Page Replacement Algorithms

### 7. 🗂️ Disk Scheduling

Implementation of algorithms used by operating systems to efficiently schedule disk requests.

* FCFS
* SSTF
* SCAN
* C-SCAN
* LOOK
* C-LOOK
* Total Head Movement
* Disk Scheduling Performance Comparison

### 8. 📁 File Management

Programs demonstrating how operating systems organize and manage files.

* File creation
* File access
* File allocation techniques
* Sequential Allocation
* Indexed Allocation
* Linked Allocation
* Directory structures
* File operations

### 9. 💿 File Allocation & Directory Management

Practical implementation and simulation of different approaches to organizing files and directories.

* Single-Level Directory
* Two-Level Directory
* Hierarchical Directory
* File Allocation Methods
* Directory Operations

### 10. 🖥️ System Calls

Programs demonstrating interaction between user programs and the operating system.

* Process-related system calls
* File-related system calls
* `open()`
* `read()`
* `write()`
* `close()`
* `fork()`
* `exec()`
* `wait()`

### 11. 🔢 Inter-Process Communication (IPC)

Understanding how processes communicate and exchange data.

* Pipes
* Shared Memory
* Message Passing
* Synchronization between processes

### 12. 🧵 Threads

Programs related to concurrent execution using threads.

* Thread creation
* Thread execution
* Thread synchronization
* Mutex locks
* Thread-based concurrency

---

## 🗺️ Repository Structure

```text
Operating-Systems-Lab/
│
├── Process-Management/
├── CPU-Scheduling/
├── Process-Synchronization/
├── Deadlocks/
├── Memory-Management/
├── Page-Replacement/
├── Disk-Scheduling/
├── File-Management/
├── File-Allocation/
├── Directory-Management/
├── System-Calls/
├── Inter-Process-Communication/
├── Threads/
│
└── README.md
```

> The folder structure may vary depending on the experiments included in the laboratory syllabus.

---

## 🎯 Learning Objectives

By completing the programs in this repository, you can develop a practical understanding of:

* How operating systems manage processes
* How CPU scheduling algorithms work
* How memory is allocated and managed
* How virtual memory works
* How page replacement is performed
* How deadlocks occur and how they can be handled
* How processes communicate with each other
* How synchronization prevents race conditions
* How files and directories are managed
* How disk requests are scheduled
* How system calls provide access to OS services

---

## 🛠️ Technologies Used

The implementations in this repository primarily use:

* **C**
* **C++**
* **Linux / Unix concepts**
* **Shell commands** where required

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone <your-repository-url>
cd Operating-Systems-Lab
```

### Compile a C Program

```bash
gcc program.c -o program
```

### Run

```bash
./program
```

### Compile a C++ Program

```bash
g++ program.cpp -o program
```

### Run

```bash
./program
```

---

## 📊 What Each Program Includes

Where applicable, programs are organized to make them easier to understand and revise:

```text
Experiment
    ↓
Problem Statement
    ↓
Algorithm / Approach
    ↓
Source Code
    ↓
Sample Input
    ↓
Sample Output
    ↓
Result / Observation
```

This structure makes the repository useful not only for **lab submissions**, but also for **exam preparation, viva revision, and understanding OS algorithms**.

---

## 🎓 Academic Use

This repository can be used as a reference for:

* Operating Systems laboratory courses
* Practical examinations
* Lab record preparation
* Viva preparation
* Algorithm practice
* Semester revision
* Understanding OS concepts through implementation

---

## 🌟 Why This Repository?

Operating Systems can be difficult to understand when studied only theoretically.

This repository follows a **learn → implement → test → understand** approach, connecting theoretical OS concepts with practical programs.

Instead of simply memorizing algorithms, the implementations help demonstrate **how and why operating-system mechanisms work**.

---

## 🤝 Contributions

If you find an issue, have a better implementation, or want to add another Operating Systems experiment, feel free to contribute.

Ideas for contribution include:

* Improving existing implementations
* Adding comments and explanations
* Adding new OS algorithms
* Improving sample outputs
* Fixing bugs
* Adding documentation

---

## 📌 Disclaimer

This repository is created for **educational and academic purposes**. The programs are intended to help students understand and practice Operating Systems concepts.

---

## 🚀 Keep Learning

> **Don't just memorize Operating Systems algorithms — implement them, experiment with them, and understand what happens underneath.**

⭐ If this repository helps you with your OS lab preparation, consider giving it a **star**!



