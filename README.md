# THREADS-Scheduler
CYBV489-Group 13
Project name: THREADS: Scheduler Milestone (SchedulerTest00)
Group number: Group 13 - Kernel Development Groups
Team Member: Adam H. Guled   Andrew Feng
This project implements a basic process scheduler for the THREADS operating system. The main test case (SchedulerTest00) creates one child process, waits for it to terminate, and then exits.
Process Management:
Process creation (k_spawn)
Process termination (k_exit)
Process waiting (k_wait)
Process switching (dispatcher)
Key Functions
bootstrap() - System initialization
k_spawn() - Create new process
k_wait() - Wait for child process
k_exit() - Terminate process
dispatcher() - Context switching
