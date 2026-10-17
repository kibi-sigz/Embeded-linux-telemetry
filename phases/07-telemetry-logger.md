# Phase 7 — Build a Telemetry Logger

[← Dashboard](../README.md) | [← Previous phase](06-sensor-interfaces.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](08-service-reliability.md)

## Goal

Build the first meaningful project: validated, timestamped measurements saved to disk.

## Lesson and practical tasks

### 1. Define a record

**Try:** Start with timestamp, source, measurement name, value, and status.

**Task:** Document units and the meaning of missing readings.

### 2. Write CSV output

**Try:** Create a Python program that appends records to a CSV file.

**Task:** Begin with simulated measurements if no sensor is available.

### 3. Validate input

**Try:** Test empty, malformed, out-of-range, and stale readings.

**Task:** Do not silently turn invalid readings into believable values.

### 4. Add SQLite

**Try:** Store the same records in a small database.

**Task:** Keep CSV as a simple export/debug option.


## Checkpoint

Can you demonstrate a reading moving from input through validation to a timestamped saved record? Include one invalid-input test.

- [ ] I completed the practical tasks.
- [ ] I can explain the key ideas without reading the lesson word for word.
- [ ] I recorded my results and next action in the [learning journal](../progress/LEARNING_LOG.md).
- [ ] I updated the [progress tracker](../progress/TRACKER.md).

**Continue:** [Next phase →](08-service-reliability.md)
