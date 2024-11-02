# operating-system-notes

## 1. What is an operating system?
Ans: An operating system is a software that acts as an interface between computer hardware and user applications. It manages resources and provides services for the efficient and secure execution of a program. The primary functions of an operating system include process management, memory management, file system management, resource management and user interface.

## 2. Types of operating system:
1. Windows : Microsoft
2. macOS : Apple
3. Linux : Linus Torvalds, Open-Source
4. Unix : multi-user OS
5. Android : Google, open-source
6. iOS : Apple
7. RTOS : Real Time Operating Systems

## 3. What is multiprocessing?
Ans: Multiprocessing refers to the concurrent execution of multiple processes on a system with multiple cpus or cpu cores. Each process has its own memory space and resources. Multiprocessing aims at increasing the system's throughput and provides faster execution by distributing the workload across multiple processors.

## 4. What is multithreading?
Ans: Multithreading refers to concurrent execution of multiple threads within a single process. A thread is a lightweight unit of execution that can run concurrently with other threads within the same process. Threads share same memory space and resources. Multithreading allows for parallel execution within a process enabling better utilization of system's resources and potentially improving performance by dividing the tasks into smaller units of work that can be executed concurrently.

## 5. What is multiprogramming?
Ans: Multiprogramming a technique where multiple programs are loaded into the main memory simultaneously and CPU switches between them to execute instructions. The main purpose of multiprogramming is to maximize CPU utilization and to keep CPU busy by quickly switching between different programs when one is waiting for I/O or other operations. Each program has it's own separate memory space.

## 6. What is multitasking?
Ans: Multitasking is a technique that allows multiple tasks or processes to run concurrently on a single CPU. The CPU time is divided among the tasks giving the illusion of parallel execution. Multitasking is used in modern operating systems to provide responsiveness and the ability to run multiple applications simultaneously.

## 7. What is a program?
Ans: A program is a set of instructions written in a programming language that performs a specific task or set of tasks. A program is typically stored in a file on disk and represents an executable entity. Programs can either be compiled or interpreted depending upon the type of programming language.

## 8. What is a process?
Ans: A process is an instance of program in execution. When a program is loaded into main memory and executed, then it becomes a process. A process is an independent entity with its own memory space, resources and execution context. It has its own program counter and stack. Processes can be concurrent and can communicate with each other through inter-process communication.

## 9. What is a thread?
Ans: A thread is a lightweight unit of execution within a process. It represents a sequence of instructions that can be scheduled and executed independently. Threads share the same memory space and resources within a process. However, each thread has its own program counter and stack. Multiple threads within a process can run concurrently, allowing for parallel execution of tasks.





