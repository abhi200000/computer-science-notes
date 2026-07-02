# Process States

## Definition

A process goes through different states during its execution in the Operating System.

These states help the OS manage and schedule processes efficiently.

---

## Process States

### 1. New

When a process is created.

Example:
- When you open Chrome, a new process is created.

---

### 2. Ready

The process is loaded into memory and is waiting for CPU.

It is ready to execute but CPU is not assigned yet.

---

### 3. Running

The process is currently being executed by the CPU.

Only one process can run on a single core at a time.

---

### 4. Waiting (Blocked)

The process is waiting for some event to occur.

Example:
- Waiting for user input
- Waiting for file I/O

---

### 5. Terminated

The process has finished execution or is killed by the OS.

---

## Process State Diagram

```
New → Ready → Running → Terminated
              ↓
           Waiting
              ↓
             Ready
```

---

## Real-Life Example

Imagine making tea:

- New → You decide to make tea
- Ready → Ingredients are ready
- Running → You are making tea
- Waiting → Waiting for water to boil
- Terminated → Tea is ready

---

## Important Transitions

- Ready → Running (CPU assigned)
- Running → Waiting (I/O request)
- Waiting → Ready (Event completed)
- Running → Terminated (Execution finished)

---

## Interview Questions

### 1. What are process states?

Process states represent different phases of a process during execution in OS.

---

### 2. What is Ready state?

A state where process is waiting for CPU allocation.

---

### 3. What is Waiting state?

A state where process is waiting for I/O or event completion.

---

### 4. What is the difference between Ready and Running?

- Ready: Waiting for CPU
- Running: Currently using CPU

---

## Key Points

- A process does not stay in one state.
- It moves between states based on CPU and I/O.
- OS manages transitions.
- Helps in scheduling and multitasking.