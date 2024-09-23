# Named Pipe Chat Application

A simple chat application that demonstrates inter-process communication using named pipes (FIFOs) in C. The application allows two users to send messages to each other in a terminal.

## Overview

This project consists of two programs, `user1.c` and `user2.c`, that communicate through a named pipe. Users take turns to send and receive messages in a console interface.

## Features

- **Real-time messaging**: Users can send and receive messages in real-time.
- **Named pipes**: Utilizes the `mkfifo` system call to create a FIFO for communication.
- **Simple terminal interface**: User-friendly command-line interface for interaction.

## Requirements

- A Linux-based operating system
- GCC (GNU Compiler Collection)
- Basic knowledge of C programming and terminal commands

## How to Compile and Run

### Compile the Programs

```
user terminal 1 : 
 gcc user1.c
./a.out

user terminal 2 : 
 gcc user2.c
./a.out
```
