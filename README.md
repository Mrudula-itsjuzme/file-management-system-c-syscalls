# File Management System using C System Calls

## Overview

A low-level file management system implemented in C, leveraging Unix system calls for efficient file operations. This project is part of a portfolio focused on system-level programming and AI systems.

## Project Structure

- **src/**: Core C source files including `main.c` and `backend.c`.
- **docs/**: Architectural diagrams and methodology documentation.
- **tests/**: Scripts and source files for verifying system performance and correctness.
- **Makefile**: Build automation for compiling the project.

## Implementation Details

The system provides robust handling for:
- File creation, reading, and writing using direct syscalls.
- Metadata management and directory traversal.
- Error handling for various system-level interruptions.

## Usage Instructions

1. Ensure a C compiler (e.g., GCC) and `make` are installed.
2. Run `make` to compile the application.
3. Execute the binary generated in the root directory.

## Future Enhancements

- Implementation of advanced file locking mechanisms.
- Expansion of the test suite to include edge-case system behaviors.
- Integration with external logging services.
