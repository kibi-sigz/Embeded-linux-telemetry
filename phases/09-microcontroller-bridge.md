# Phase 9 — Microcontroller-to-Pi Bridge

[← Dashboard](../README.md) | [← Previous phase](08-service-reliability.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](10-portfolio.md)

## Goal

Send structured data from an MCU or simulator to the Pi over UART.

## Lesson and practical tasks

### 1. Define a small packet

**Try:** Specify delimiter or framing, fields, units, and version.

**Task:** Choose a simple format and document examples.

### 2. Simulate first

**Try:** Generate sample lines on the Pi before connecting hardware.

**Task:** This separates protocol bugs from wiring problems.

### 3. Connect hardware carefully

**Try:** Verify the exact board pinout, logic voltage, TX/RX direction, and ground.

**Task:** Disconnect power before wiring; never assume a board's pins are 5 V tolerant.

### 4. Validate packets

**Try:** Reject malformed or incomplete packets and count errors.

**Task:** Keep the logger running when a packet is invalid.


## Checkpoint

Can you explain your packet format and demonstrate the receiver rejecting a malformed message?

- [ ] I completed the practical tasks.
- [ ] I can explain the key ideas without reading the lesson word for word.
- [ ] I recorded my results and next action in the [learning journal](../progress/LEARNING_LOG.md).
- [ ] I updated the [progress tracker](../progress/TRACKER.md).

**Continue:** [Next phase →](10-portfolio.md)
