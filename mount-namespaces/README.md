# Mount Namespaces - XV6

Implemented mount namespaces in the XV6 kernel - the same mechanism that powers
filesystem isolation in Linux containers (Docker, Podman).

`mnt_ns.c` adds a mount namespace table to the kernel, allowing processes to have
independent views of the filesystem mount tree.
