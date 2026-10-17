# Phase 6 — Sensor Interfaces: UART, I²C and SPI

[← Dashboard](../README.md) | [← Previous phase](05-c-on-linux.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](07-telemetry-logger.md)

## Goal

Understand the common interfaces used by sensors and embedded hardware.

## Lesson and practical tasks

### 1. Compare the buses

**Try:** Write down wire count, typical use, and key trade-offs for UART, I²C, and SPI.

**Task:** Remember that details depend on the actual hardware.

### 2. Inspect interfaces

**Try:** `ls -l /dev/serial* /dev/i2c* 2>/dev/null`

**Task:** An interface may be disabled or absent; do not assume that means hardware is broken.

### 3. Choose an existing driver/library

**Try:** Use the manufacturer's documentation for your exact sensor.

**Task:** Start with userspace tools/libraries before considering a kernel driver.


## Checkpoint

Can you choose a suitable interface for one sensor and explain the voltage, pinout, and driver checks required before wiring?

- [ ] I completed the practical tasks.
- [ ] I can explain the key ideas without reading the lesson word for word.
- [ ] I recorded my results and next action in the [learning journal](../progress/LEARNING_LOG.md).
- [ ] I updated the [progress tracker](../progress/TRACKER.md).

**Continue:** [Next phase →](07-telemetry-logger.md)
