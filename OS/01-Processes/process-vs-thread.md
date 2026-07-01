# Process vs Thread

## Definition

### What is a Process?

A process is a program that is currently running. It has its own memory, resources, and Process ID (PID).

**Examples:**
- Google Chrome
- Visual Studio Code
- Spotify

---

### What is a Thread?

A thread is the smallest unit of execution inside a process.

A process can have one or more threads that share the same memory and resources.

---

## Difference Between Process and Thread

| Process | Thread |
|----------|--------|
| Independent program in execution | Smallest unit of execution |
| Has its own memory | Shares memory with other threads |
| Creation is slower | Creation is faster |
| Context switching is slower | Context switching is faster |
| Communication is slower | Communication is faster |
| More secure | Less secure because memory is shared |

---

## Real-Life Example

Imagine a restaurant.

**Process = Restaurant**

The restaurant has its own building, kitchen, staff, and resources.

**Threads = Workers**

- One worker takes orders.
- One worker cooks food.
- One worker collects payment.

All workers share the same restaurant resources.

---

## Advantages of Process

- Better security
- Independent execution
- One process crashing usually does not affect another process

---

## Advantages of Thread

- Faster execution
- Better CPU utilization
- Lower memory usage
- Faster communication
- Easy resource sharing

---

## Interview Questions

### 1. What is a Process?

A process is a program in execution with its own memory and resources.

### 2. What is a Thread?

A thread is the smallest unit of execution inside a process.

### 3. Why are threads faster than processes?

Threads share the same memory and resources, so they are cheaper to create and communicate faster.

### 4. Can a process have multiple threads?

Yes. This is called a multithreaded process.

Examples:
- Google Chrome
- Visual Studio Code
- Microsoft Word

---

## Key Points

- Process is heavyweight.
- Thread is lightweight.
- Process has separate memory.
- Threads share memory.
- Process creation is slower.
- Thread creation is faster.
- Process communication is slower.
- Thread communication is faster.