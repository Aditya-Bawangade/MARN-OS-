# MARN OS

MARN OS is a learning operating system project implemented using Assembly and C for Intel x86 machines. This project focuses on implementing interrupts and interrupt handling, extending the capabilities of a basic OS codebase.

<table>
    <tr>
        <td><img src="https://github.com/user-attachments/assets/4401d3d7-8f41-454d-880b-a4d17ea837c3" alt="Image 1" width="400"></td>
        <td><img src="https://github.com/user-attachments/assets/d5ae13ea-0eed-48a5-8896-bcd06bd0259d" alt="Image 2" width="400"></td>
    </tr>
    <tr>
        <td  style="text-align: center;">Loading screen for MARN OS</td>
        <td  style="text-align: center;">Timer interrupt and Keyboard interrupt being handled</td>
    </tr>
</table>




## Project Team
- Mohammad Senan Ali (2104218)
- Aditya Rajesh Bawangade (2103111)
- Rishabh Jain (2104226)
- Nishant Kumar Singh (2104221)

## Features

- Implemented interrupts and interrupt handling using assembly and C programs
- Enhanced and extended capabilities for interrupt creation and handling
- Implemented Interrupt Descriptor Table (IDT) for x86 architecture
- Handling of various types of interrupts:
  - Software Interrupts
  - Hardware Interrupts
  - User-defined Interrupts
- Exception handling for scenarios like division by zero and overflow errors
- Implementation of Programmable Interrupt Controller (PIC)
- Handling of hardware interrupts:
  - Timer (IRQ0)
  - Keyboard (IRQ1)

## Key Components

1. **Interrupt Descriptor Table (IDT)**: Manages and routes interrupts and exceptions
2. **Programmable Interrupt Controller (PIC)**: Manages hardware interrupts
3. **Exception Handlers**: Custom handlers for various system exceptions
4. **Hardware Interrupt Handlers**: Handlers for timer and keyboard interrupts
5. **User-defined Interrupts**: Custom interrupts for extended functionality

## Building and Running

To build this project you need to run the  `Makefile`.
To run simply run `run.sh`

## Project Structure
```
project-root/
|
|
├── build_scripts
│
├── build
|    └── ... (kernel files)
├── src      
│   └── bootloader
|   └── kernel
|    
├── tools     
|          └── fat (filesystem)                  
├── debug.sh
├── run.sh
└── README.md
```
## Acknowledgement

This project is part of the CS310 Operating Systems course under Prof. Shitala Prasad. 

## Resources

- [Intel 80386 Reference Programmer's Manual](https://pdos.csail.mit.edu/6.828/2018/readings/i386/c09.htm)
- [The Netwide Assembler](https://www.nasm.us/doc/)
- [OSdev](https://wiki.osdev.org/Getting_Started)



