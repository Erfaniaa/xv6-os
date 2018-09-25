# xv6 Operating System with Process Migration
> It was a project for Operating Systems course of Shahid Beheshti University

Project full statement in Persian: [https://github.com/Erfaniaa/xv6-public/OS_Project_Statement.pdf](https://github.com/Erfaniaa/xv6-public/OS_Project_Statement.pdf)

Purpose of doing this project is to add "process migration" feature to MIT xv6 OS.

In fact, process migration contains these steps:
1. Start a process.
2. Save the state of that process in a file.
3. Terminate that process.
4. Read the file and start a new process by loading the saved state.

Using this method, we may migrate processes from a computer to other computers.

## Dependencies

First of all, install QEMU.

## Installation and Usage

```sh
make
make qemu
```

```sh
usertests
```
