# Phase 4 — Python Environments and Serial I/O

[← Dashboard](../README.md) | [← Previous phase](03-hardware-discovery.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](05-c-on-linux.md)

## Goal

Use a project-specific Python environment and understand serial input.

## Lesson and practical tasks

### 1. Create a virtual environment

**Try:** `cd ~/embedded-telemetry && python3 -m venv .venv`

**Task:** If venv support is missing, record the exact error before installing anything.

### 2. Activate and install pyserial

**Try:** `source .venv/bin/activate` then `python -m pip install pyserial`

**Task:** Use the environment's Python and pip.

### 3. Inspect serial ports

**Try:** `python -m serial.tools.list_ports -v`

**Task:** A physical serial device is optional for this phase.


## Checkpoint

Can you explain why a virtual environment is useful and how your program should handle timeouts or malformed serial data?

- [ ] I completed the practical tasks.
- [ ] I can explain the key ideas without reading the lesson word for word.
- [ ] I recorded my results and next action in the [learning journal](../progress/LEARNING_LOG.md).
- [ ] I updated the [progress tracker](../progress/TRACKER.md).

**Continue:** [Next phase →](05-c-on-linux.md)
