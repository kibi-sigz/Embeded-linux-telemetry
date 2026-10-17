# Phase 5 — C Programming on Linux

[← Dashboard](../README.md) | [← Previous phase](04-python-serial.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](06-sensor-interfaces.md)

## Goal

Compile a tiny C program and understand the edit-compile-run loop.

## Lesson and practical tasks

### 1. Check compiler

**Try:** `gcc --version`

**Task:** If missing, note your OS and install instructions; do not use sudo without understanding the command.

### 2. Create a program

**Try:** Save a small `hello.c` that includes stdio.h and prints a line.

**Task:** Compile with `gcc -Wall -Wextra -o hello hello.c`, then run `./hello`.

### 3. Make one deliberate error

**Try:** Temporarily misspell a function name, compile, and read the diagnostic.

**Task:** Fix it immediately and compile again.


## Checkpoint

Can you explain what the compiler produces, how to run the executable, and how you used an error message to fix the program?

- [ ] I completed the practical tasks.
- [ ] I can explain the key ideas without reading the lesson word for word.
- [ ] I recorded my results and next action in the [learning journal](../progress/LEARNING_LOG.md).
- [ ] I updated the [progress tracker](../progress/TRACKER.md).

**Continue:** [Next phase →](06-sensor-interfaces.md)
