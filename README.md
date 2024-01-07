# VortexOS

## Project Overview
Developed a multi-tasking operating system as part of a team project. The project involved booting into protected mode, setting up essential components such as the GDT, IDT, and basic paging support. Key functionalities included initializing devices (keyboard, RTC), supporting system calls, creating a terminal driver, parsing a read-only file system, and executing user-level code.

## Key Features
- GDT and IDT Initialization
- Device Initialization (PIC, keyboard, RTC)
- Paging Support for Kernel and User Tasks
- Terminal Driver Implementation
- File System Parsing
- System Calls Implementation
- User-Level Code Execution
- Process Control Block and Task Management
- Multi-Terminal Support
- Round-Robin Task Scheduling

## Achievements
- Successfully handled exceptions and interrupts for device input (keyboard, RTC).
- Implemented a terminal driver supporting various functionalities, including vertical scrolling, backspace, and line-buffered input.
- Developed a file system parser for reading files and directories from a read-only file system image.
- Implemented a scheduler for task switching, with support for up to six processes and three terminals.
- Ensured proper handling of virtual memory remapping to prevent inactive tasks from writing to the screen.

## Technologies Used
- Intel IA-32 Architecture
- x86 Assembly Language
- C Programming Language

## Usage
For detailed instructions on building, running, and testing the operating system, refer to the project documentation.

## License
This project is licensed under [MIT License](LICENSE).

