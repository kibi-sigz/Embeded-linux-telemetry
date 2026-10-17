# Phase 2 — Processes, Services and Logs

[← Dashboard](../README.md) | [← Previous phase](01-linux-basics.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](03-hardware-discovery.md)

## Goal

Learn how Linux runs programs, applies permissions, and records problems.

## Lesson and practical tasks

### 1. Inspect processes

**Try:** `ps aux`, `top`

**Task:** Find a process and explain what a process is.

### 2. Inspect identity and permissions

**Try:** `whoami`, `id`, `ls -l`

**Task:** Explain owner, group, and read/write/execute permissions.

### 3. Inspect services and logs

**Try:** `systemctl --type=service --state=running`, `journalctl -b -p warning`

**Task:** Read output carefully; some services may differ by OS.


## Checkpoint

Can you explain the difference between a process, a service, and a log? Find one warning or explain how you would inspect one safely.

- [ ] I completed the practical tasks.
- [ ] I can explain the key ideas without reading the lesson word for word.
- [ ] I recorded my results and next action in the [learning journal](../progress/LEARNING_LOG.md).
- [ ] I updated the [progress tracker](../progress/TRACKER.md).

**Continue:** [Next phase →](03-hardware-discovery.md)
