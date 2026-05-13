# File Management System using C System Calls

A low-level file-management project implemented in C using Unix system calls.

This repository focuses on understanding how file operations work closer to the operating-system layer instead of relying only on high-level library abstractions.

---

## Problem statement

Most file operations are hidden behind standard library functions. This project explores direct system-call-based file handling to understand how operating systems manage files, metadata, errors, and directory operations.

---

## Features

- file creation
- file reading and writing
- directory traversal
- metadata handling
- low-level error handling
- Makefile-based compilation
- test scripts for correctness checks

---

## System overview

```text
User Operation
      ↓
C Application Logic
      ↓
Unix System Calls
      ↓
Kernel File Interface
      ↓
Filesystem
```

---

## Repository structure

```text
file-management-system-c-syscalls/
├── src/        # C source files such as main.c and backend.c
├── docs/       # architecture and methodology notes
├── tests/      # test scripts and verification files
├── Makefile    # build automation
└── README.md
```

---

## Build and run

```bash
git clone https://github.com/Mrudula-itsjuzme/file-management-system-c-syscalls.git
cd file-management-system-c-syscalls

make
```

Run the generated executable from the root directory.

---

## Tech stack

- C
- Unix/Linux system calls
- GCC
- Makefile
- Operating-system concepts

---

## Learning outcomes

This project demonstrates practical understanding of:

- how file descriptors work
- how read/write operations interact with the OS
- how low-level errors are handled
- how directory traversal works
- how build automation is managed in C projects

---

## Future improvements

- add file-locking support
- expand tests for edge cases
- add command-line flags
- include screenshots or terminal output examples
- add logging for failed system calls

---

## Author

Built by [Pedamallu Sai Mrudula](https://github.com/Mrudula-itsjuzme) as part of a systems-programming and operating-systems portfolio.
