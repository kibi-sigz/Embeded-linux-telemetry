# Phase 3 — Hardware Discovery

[← Dashboard](../README.md) | [← Previous phase](02-processes-and-logs.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](04-python-serial.md)

## Goal

Identify connected USB and serial hardware before writing code.

## Lesson and practical tasks

### 1. List USB devices

**Try:** `lsusb` (install package only if needed)

**Task:** Record device names without exposing private identifiers.

### 2. Watch kernel messages

**Try:** `dmesg --follow`

**Task:** Plug in a non-critical USB device and observe new messages; stop with Ctrl+C.

### 3. Find serial paths

**Try:** `ls -l /dev/serial/by-id/`

**Task:** If the path does not exist, record that; not every system has this directory.


## Checkpoint

Can you identify a device path and explain why stable `/dev/serial/by-id/` paths can be preferable to guessing `/dev/ttyUSB0`?

- [ ] I completed the practical tasks.
- [ ] I can explain the key ideas without reading the lesson word for word.
- [ ] I recorded my results and next action in the [learning journal](../progress/LEARNING_LOG.md).
- [ ] I updated the [progress tracker](../progress/TRACKER.md).

**Continue:** [Next phase →](04-python-serial.md)
