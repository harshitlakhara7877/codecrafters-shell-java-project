# Build Your Own Shell (Java)

A Unix-like shell implementation built in Java as part of the Operating Systems coursework using the CodeCrafters Shell Challenge.

## Project Overview

This project aims to implement a simplified command-line shell similar to Unix/Linux shells such as Bash. The shell is developed incrementally through the CodeCrafters Shell Challenge, helping understand how operating systems execute commands, manage processes, handle file descriptors, and perform inter-process communication.

The primary objective of this project is to bridge Operating Systems theory with practical implementation.

---

## Features

### Base Shell

* Interactive REPL (Read-Evaluate-Print Loop)
* Shell prompt display
* Command parsing
* Invalid command handling
* Built-in commands:

  * `echo`
  * `exit`
  * `type`

### Planned Features

* PATH-based executable lookup
* External command execution
* Directory navigation (`pwd`, `cd`)
* Command quoting and escaping
* Input/Output redirection
* Background job execution
* Job management
* Pipelines
* Process reaping

---

## Operating Systems Concepts Covered

This project provides hands-on experience with:

* Shell Architecture
* REPL Loop
* Command Parsing
* Built-in Commands
* Process Creation
* Process Execution
* Environment Variables
* PATH Lookup
* Current Working Directory (CWD)
* File Descriptors
* Standard Input, Output, and Error Streams
* Input/Output Redirection
* Background Processes
* Process Reaping
* Pipes and Pipelines
* Inter-Process Communication (IPC)

---

## Current Progress

### Completed

* Shell Prompt
* REPL Loop
* `echo` Built-in Command
* `exit` Built-in Command
* `type` Built-in Command
* Invalid Command Handling

### In Progress

* PATH Lookup
* External Command Execution

### Upcoming Modules

* Navigation
* Quoting
* Redirection
* Background Jobs
* Pipelines

---

## Example Usage

### Echo

```bash
$ echo Hello World
Hello World
```

### Type

```bash
$ type echo
echo is a shell builtin
```

### Invalid Command

```bash
$ abc
abc: command not found
```

### Exit

```bash
$ exit 0
```

---

## Project Structure

```text
src/
└── main/
    └── java/
        └── Main.java
```

---

## Technologies Used

* Java
* Maven
* Git
* GitHub
* CodeCrafters Shell Challenge

---

## Learning Outcomes

By building this shell, I aim to gain a practical understanding of:

* How shells execute commands
* How processes are created and managed
* How operating systems handle command execution
* How standard streams and file descriptors work
* How processes communicate using pipes
* How background jobs are tracked and cleaned up

---

## References

* CodeCrafters Shell Challenge
* Java Documentation
* Operating Systems Course Material
* Unix/Linux Shell Documentation

---

## Author

Harshit Lakhara

Operating Systems Assignment – Build Your Own Shell Using Java
