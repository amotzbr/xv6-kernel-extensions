# Extended Syscalls — XV6

Added multiple system calls to the XV6 kernel:

| Syscall | Description |
|---|---|
| `usleep` | Sleep for a given number of microseconds |
| `ioctl` | I/O device control |
| `getppid` | Get parent process ID |
| `getcpu` | Get the CPU the process is running on |
| `getmem` | Get process memory usage |
| `kmemtest` | Test kernel memory allocator |
| `cps126` | List all running processes (extended from assignment 11) |
