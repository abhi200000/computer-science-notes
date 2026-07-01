# Process Control Block (PCB)

## Definition

A Process Control Block (PCB) is a data structure used by the Operating System to store all information about a process.

Whenever a new process is created, the Operating System also creates a PCB for that process.

The PCB helps the Operating System manage and track the process.

---

## Why Do We Need PCB?

The Operating System may run many processes at the same time.

To manage each process efficiently, it stores all important information in a PCB.

Without a PCB, the Operating System cannot:
- Track a process
- Schedule a process
- Pause and resume a process
- Perform context switching

---

## Information Stored in PCB

### 1. Process ID (PID)

A unique ID assigned to every process.

Example:
- Chrome → PID 1204
- VS Code → PID 2450

---

### 2. Process State

Shows the current state of the process.

Examples:
- New
- Ready
- Running
- Waiting
- Terminated

---

### 3. Program Counter (PC)

Stores the address of the next instruction to be executed.

This helps the process continue from the correct point after interruption.

---

### 4. CPU Registers

Stores the values of CPU registers while the process is executing.

These values are restored when the process runs again.

---

### 5. CPU Scheduling Information

Stores scheduling information such as:
- Priority
- Queue information
- Scheduling algorithm

The CPU scheduler uses this information to decide which process should run next.

---

### 6. Memory Management Information

Stores memory-related information such as:
- Base address
- Limit registers
- Page table
- Segment table

---

### 7. I/O Status Information

Stores information about:
- Open files
- Input devices
- Output devices
- Resources allocated to the process

---

## Real-Life Example

Imagine a school.

Every student has a record card containing:
- Roll Number
- Name
- Class
- Attendance
- Marks

Similarly, every process has a PCB containing all its important information.

---

## Advantages of PCB

- Keeps track of processes
- Makes scheduling easier
- Helps in context switching
- Efficient process management
- Stores complete process information

---

## Interview Questions

### 1. What is PCB?

PCB is a data structure used by the Operating System to store information about a process.

---

### 2. Who creates the PCB?

The Operating System creates a PCB whenever a new process is created.

---

### 3. Can a process exist without a PCB?

No.

Every process must have a PCB because the Operating System uses it to manage the process.

---

### 4. What is stored in a PCB?

- Process ID
- Process State
- Program Counter
- CPU Registers
- Scheduling Information
- Memory Information
- I/O Status Information

---

## Key Points

- PCB stands for Process Control Block.
- Every process has one PCB.
- PCB is created by the Operating System.
- PCB stores all information about a process.
- PCB is essential for process management.
- PCB is required for context switching.