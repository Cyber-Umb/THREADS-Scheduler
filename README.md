# THREADS-Scheduler

**CYBV489 - Group 13**

---

## Project Name
**THREADS: Scheduler Milestone**  
_Test Case: SchedulerTest00_

---

## Group Members
- **Adam H. Guled**  
- **Andrew Feng**

---

## Project Overview

This project implements a basic process scheduler for the THREADS operating system. The primary test case (`SchedulerTest00`) is designed to:
1. Create a single child process.  
2. Wait for the child process to terminate.  
3. Exit gracefully after execution.  

---

## Process Management Features

- **Process Creation**: (`k_spawn`) Spawns new processes.  
- **Process Termination**: (`k_exit`) Handles clean process exits.  
- **Process Waiting**: (`k_wait`) Waits for child processes to finish.  
- **Process Switching**: (`dispatcher`) Switches between ready processes.  

---

## Key Functions

### 1. **`bootstrap()`**
Initializes the operating system and starts essential processes.

### 2. **`k_spawn()`**
Handles the creation of new processes and adds them to the process table.

### 3. **`k_wait()`**
Allows a parent process to wait until a child process finishes execution.

### 4. **`k_exit()`**
Terminates the current process and cleans up resources.

### 5. **`dispatcher()`**
Performs context switching to enable multitasking between processes.

---
