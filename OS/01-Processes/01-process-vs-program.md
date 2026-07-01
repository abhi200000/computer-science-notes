# Process vs Program

## Definition

### What is a Program?

A program is a set of instructions written by a programmer to perform a specific task.

A program is stored on disk and does not execute until it is run.

**Examples:**
- Google Chrome.exe
- VS Code.exe
- Calculator.exe

---

### What is a Process?

A process is a program that is currently running.

When a program starts executing, the operating system creates a process.

A process has:
- Process ID (PID)
- Memory
- CPU time
- System resources

---

## Difference Between Program and Process

| Program | Process |
|---------|---------|
| Set of instructions | Program in execution |
| Stored on disk | Stored in main memory (RAM) while running |
| Passive | Active |
| No CPU is allocated | CPU is allocated for execution |
| Does not have a PID | Has a unique Process ID (PID) |

---

## How It Works

```
Program (.exe file)
        ↓
User opens the program
        ↓
Operating System loads it into memory
        ↓
Program becomes a Process
```

---

## Real-Life Example

Think of a recipe.

**Program = Recipe Book**

The recipe is written on paper but nothing is being cooked.

**Process = Cooking**

When a chef starts following the recipe and cooking, the recipe becomes a running activity.

---

## Advantages of Program

- Easy to store
- Can be copied and shared
- Uses very little memory when not running

---

## Advantages of Process

- Executes tasks
- Uses CPU and memory
- Can interact with users and other processes

---

## Interview Questions

### 1. What is a Program?

A program is a set of instructions stored on disk.

### 2. What is a Process?

A process is a program that is currently executing.

### 3. Can one program create multiple processes?

Yes.

Example:
Opening Google Chrome multiple times creates multiple processes.

### 4. Does every process come from a program?

Yes. Every process starts from a program.

---

## Key Points

- Program is passive.
- Process is active.
- Program is stored on disk.
- Process runs in memory (RAM).
- Program becomes a process when executed.
- Every process has a unique PID.