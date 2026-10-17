# Phase 8 — Reliability and systemd

[← Dashboard](../README.md) | [← Previous phase](07-telemetry-logger.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](09-microcontroller-bridge.md)

## Goal

Make the logger diagnosable and able to restart predictably.

## Lesson and practical tasks

### 1. Add useful logs

**Try:** Record startup, device connection, invalid data, and errors.

**Task:** Avoid logging secrets or unnecessarily precise personal location.

### 2. Create a service only after manual testing

**Try:** Follow documentation for your OS and use a dedicated working directory.

**Task:** Inspect the unit carefully before enabling it at boot.

### 3. Inspect service health

**Try:** Use `systemctl status SERVICE_NAME` and `journalctl -u SERVICE_NAME`.

**Task:** Replace SERVICE_NAME with your actual service name.


## Checkpoint

Can you explain how you would diagnose a logger that starts and then exits? Do not enable an untested service on a mission-critical system.

- [ ] I completed the practical tasks.
- [ ] I can explain the key ideas without reading the lesson word for word.
- [ ] I recorded my results and next action in the [learning journal](../progress/LEARNING_LOG.md).
- [ ] I updated the [progress tracker](../progress/TRACKER.md).

**Continue:** [Next phase →](09-microcontroller-bridge.md)
