# XV6 Kernel Extensions

Kernel-level modifications to [XV6](https://github.com/mit-pdos/xv6-public), MIT's teaching Unix OS.
Each folder contains only the files I added or modified — not the full XV6 source.

| Project | Description |
|---|---|
| [ps-syscall](./ps-syscall) | Added `cps126` system call — a `ps`-like command listing all running processes |
| [extended-syscalls](./extended-syscalls) | Added `usleep`, `ioctl`, `getppid`, `getcpu`, `getmem`, `kmemtest` system calls |
| [mount-namespaces](./mount-namespaces) | Implemented mount namespaces in the kernel — the mechanism behind container isolation |

## What is XV6?
XV6 is a real Unix kernel (based on Unix V6) developed at MIT for teaching operating systems.
Working in XV6 means writing C code that runs directly in kernel space - managing processes, memory, and system calls.
