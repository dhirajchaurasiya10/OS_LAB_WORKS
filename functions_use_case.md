# LAB ASSIGNMENT
Dhiraj Kumar Chaurasiya
(PAS078BEI012)

## Question: Describe and discuss the use case of following:

### 1. fork()
The `fork()` system function is a basic process in operating systems. It creates a new process by replicating the calling process. The new process is referred to as the child process, and the calling process as the parent process. The `fork` system function is used to start a new process that runs simultaneously with the parent. When a new child process is formed, both processes will execute the next instruction after the `fork()` system call.

### 2. exec()
`exec` is a feature of an operating system that runs an executable file in the context of an already running process, replacing the previous one. It is used to replace the existing shell process with a new one. This implies that when you use the `exec` command, the current shell process is terminated and a new one starts.

### 3. getpid()
The `getpid()` method is straightforward to use and requires no parameters. It returns the PID of the process that invoked it. When a parent process uses `fork()` to generate a child process, it may manage and coordinate the two processes using `getpid()` (as well as `getppid()`, which returns the parent process ID).

### 4. wait()
In operating systems, a parent process uses the `wait()` function to wait for the termination of its child processes. When a parent process invokes `wait()`, it stops execution until one of its child processes terminates or a signal arrives. In instances when a parent process creates several child processes, `wait()` aids in managing the lifespan of each child process by waiting for their termination one by one.

### 5. stat()
The `stat()` function in operating systems retrieves information about a file or directory. It offers information about the file's size, rights, owner, and timestamps. This function is widely used in file management and system development. The `stat()` method obtains a file's status and puts it in a structure with fields indicating various file properties.

### 6. opendir()
In operating systems, the `opendir()` function opens a directory stream. This directory stream may then be used to read the directory's contents using methods such as `readdir()` and shut it with `closedir()`. `opendir()` is frequently used in utilities that require to manage or analyze directory contents, such as backup programs, file managers, and custom scripts.

### 7. readdir()
The `readdir()` function in operating systems is used to read directory entries from a directory stream that has been opened using `opendir()`. It lets you traverse the contents of a directory and obtain information about each file or subfolder within it.

### 8. close()
In operating systems, the `close()` function closes a file descriptor, which is an integer handle that the operating system uses to identify an open file, socket, or other I/O resource. Closing a file descriptor releases its related resources and indicates that it is no longer in use.
