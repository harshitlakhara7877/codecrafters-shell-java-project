# Build Your Own Shell (Java)

A Unix-like shell implementation built in Java as part of the Operating Systems coursework using the CodeCrafters Shell Challenge.

## Overview

This project implements a simplified command-line shell that mimics the behavior of traditional Unix shells. The objective of this assignment is to understand how operating systems handle command execution, process management, file descriptors, command parsing, and inter-process communication.

The shell is developed stage-by-stage using the CodeCrafters Shell Challenge and focuses on core Operating Systems concepts rather than advanced shell convenience features.

## Features Implemented

### Base Shell

 Interactive REPL loop
# Build Your Own Shell (Java)

A Unix-like shell implementation built in Java as part of the Operating Systems coursework using the CodeCrafters Shell Challenge.

## Overview

This project implements a simplified command-line shell that mimics the behavior of traditional Unix shells. The objective of this assignment is to understand how operating systems handle command execution, process management, file descriptors, command parsing, and inter-process communication.

The shell is developed stage-by-stage using the CodeCrafters Shell Challenge and focuses on core Operating Systems concepts rather than advanced shell convenience features.

## Features Implemented

### Base Shell

# Build Your Own Shell (Java)

A Unix-like shell implementation built in Java as part of the Operating Systems coursework using the CodeCrafters Shell Challenge.

## Overview

This project implements a simplified command-line shell that mimics the behavior of traditional Unix shells. The objective of this assignment is to understand how operating systems handle command execution, process management, file descriptors, command parsing, and inter-process communication.

The shell is developed stage-by-stage using the CodeCrafters Shell Challenge and focuses on core Operating Systems concepts rather than advanced shell convenience features.

## Features Implemented

### Base Shell

* Interactive REPL loop
* Shell prompt display
* Built-in commands

  * `echo`
  * `exit`
  * `type`
* Invalid command handling
* PATH-based executable lookup
* External command execution

### Navigation

* `pwd`
* `cd` with absolute paths
* `cd` with relative paths
* `cd ~` (home directory support)

### Quoting & Parsing

* Single quotes
* Double quotes
* Escape characters
* Command tokenization
* Quoted executable execution

### Redirection

* Standard output redirection (`>`, `1>`)
* Standard error redirection (`2>`)
* Output append (`>>`, `1>>`)
* Error append (`2>>`)

### Background Jobs

* Job registration
* Background execution using `&`
* Job listing
* Job tracking
* Process reaping
* Job number recycling

### Pipelines

* Dual-command pipelines
* Multi-command pipelines
* Pipelines with built-in commands

## Operating Systems Concepts Covered

This project provides practical exposure to:

* Shell REPL Architecture
* Process Creation and Execution
* Built-in vs External Commands
* Environment Variables
* PATH Lookup Mechanism
* Current Working Directory (CWD)
* Command Parsing and Tokenization
* Standard Input / Output / Error Streams
* File Descriptors
* Output Redirection
* Background Process Execution
* Process Management
* Zombie Processes
* Process Reaping
* Pipes and Pipelines
* Inter-Process Communication (IPC)

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

### Navigation

```bash
$ pwd
/home/user

$ cd projects
```

### Redirection

```bash
$ echo hello > output.txt
```

### Background Job

```bash
$ sleep 10 &
```

### Pipeline

```bash
$ cat file.txt | grep hello | wc -l
```

## Project Structure

```text
src/
└── main/
    └── java/
        └── Main.java
```

## Technologies Used

* Java
* Maven
* CodeCrafters Shell Challenge
* Git & GitHub

## Learning Outcome

Through this project, I gained hands-on experience with how modern shells work internally and how operating systems manage processes, command execution, file descriptors, redirection, and inter-process communication.

## References

* CodeCrafters Shell Challenge
* Java Documentation
* Operating Systems Course Material
* Unix Shell Documentation
Interactive REPL loop
* Shell prompt display
* Built-in commands

  * `echo`
  * `exit`
  * `type`
* Invalid command handling
* PATH-based executable lookup
* External command execution

### Navigation

* `pwd`
* `cd` with absolute paths
* `cd` with relative paths
* `cd ~` (home directory support)

### Quoting & Parsing

* Single quotes
* Double quotes
* Escape characters
* Command tokenization
* Quoted executable execution

### Redirection

* Standard output redirection (`>`, `1>`)
* Standard error redirection (`2>`)
* Output append (`>>`, `1>>`)
* Error append (`2>>`)

### Background Jobs

* Job registration
* Background execution using `&`
* Job listing
* Job tracking
* Process reaping
* Job number recycling

### Pipelines

* Dual-command pipelines
* Multi-command pipelines
* Pipelines with built-in commands

## Operating Systems Concepts Covered

This project provides practical exposure to:

* Shell REPL Architecture
* Process Creation and Execution
* Built-in vs External Commands
* Environment Variables
* PATH Lookup Mechanism
* Current Working Directory (CWD)
* Command Parsing and Tokenization
* Standard Input / Output / Error Streams
* File Descriptors
* Output Redirection
* Background Process Execution
* Process Management
* Zombie Processes
* Process Reaping
* Pipes and Pipelines
* Inter-Process Communication (IPC)

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

### Navigation

```bash
$ pwd
/home/user

$ cd projects
```

### Redirection

```bash
$ echo hello > output.txt
```

### Background Job

```bash
$ sleep 10 &
```

### Pipeline

```bash
$ cat file.txt | grep hello | wc -l
```

## Project Structure

```text
src/
└── main/
    └── java/
        └── Main.java
```

## Technologies Used

* Java
* Maven
* CodeCrafters Shell Challenge
* Git & GitHub

## Learning Outcome

Through this project, I gained hands-on experience with how modern shells work internally and how operating systems manage processes, command execution, file descriptors, redirection, and inter-process communication.

## References

* CodeCrafters Shell Challenge
* Java Documentation
* Operating Systems Course Material
* Unix Shell Documentation
Shell prompt display
* Built-in commands

  * `echo`
  * `exit`
  * `type`
* Invalid command handling
* PATH-based executable lookup
* External command execution

### Navigation

* `pwd`
* `cd` with absolute paths
* `cd` with relative paths
* `cd ~` (home directory support)

### Quoting & Parsing

* Single quotes
* Double quotes
* Escape characters
* Command tokenization
* Quoted executable execution

### Redirection

* Standard output redirection (`>`, `1>`)
* Standard error redirection (`2>`)
* Output append (`>>`, `1>>`)
* Error append (`2>>`)

### Background Jobs

* Job registration
* Background execution using `&`
* Job listing
* Job tracking
* Process reaping
* Job number recycling

### Pipelines

* Dual-command pipelines
* Multi-command pipelines
* Pipelines with built-in commands

## Operating Systems Concepts Covered

This project provides practical exposure to:

* Shell REPL Architecture
* Process Creation and Execution
* Built-in vs External Commands
* Environment Variables
* PATH Lookup Mechanism
* Current Working Directory (CWD)
* Command Parsing and Tokenization
* Standard Input / Output / Error Streams
* File Descriptors
* Output Redirection
* Background Process Execution
* Process Management
* Zombie Processes
* Process Reaping
* Pipes and Pipelines
* Inter-Process Communication (IPC)

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

### Navigation

```bash
$ pwd
/home/user

$ cd projects
```

### Redirection

```bash
$ echo hello > output.txt
```

### Background Job

```bash
$ sleep 10 &
```

### Pipeline

```bash
$ cat file.txt | grep hello | wc -l
```

## Project Structure

```text
src/
└── main/
    └── java/
        └── Main.java
```

## Technologies Used

* Java
* Maven
* CodeCrafters Shell Challenge
* Git & GitHub

## Learning Outcome

Through this project, I gained hands-on experience with how modern shells work internally and how operating systems manage processes, command execution, file descriptors, redirection, and inter-process communication.

## References

* CodeCrafters Shell Challenge
* Java Documentation
* Operating Systems Course Material
* Unix Shell Documentation
