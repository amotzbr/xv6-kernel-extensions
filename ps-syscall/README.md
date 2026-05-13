# ps syscall — XV6

Added a `cps126` system call to XV6 that prints a table of all running processes,
similar to the Unix `ps` command.

**Modified files:**
- `proc.c` — kernel implementation of `cps126()`
- `sysproc.c` — `sys_cps126` syscall handler
- `syscall.c` — syscall dispatch table
- `user.h` / `usys.S` — user-space interface
- `defs.h` — kernel function declarations
- `ps.c` — user-space program that calls the syscall
