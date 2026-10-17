# Embedded Linux & Telemetry — Interactive Learning Course

**Start here.** This repository is designed as a linked course: open a phase, do the lesson, record your progress, then follow **Next phase →**.

## Your dashboard

- **Current focus:** Phase 1 — Linux Basics
- **Progress tracker:** [Open `progress/TRACKER.md`](progress/TRACKER.md)
- **Learning journal:** [Open `progress/LEARNING_LOG.md`](progress/LEARNING_LOG.md)
- **Safety rules:** [Open `SAFETY.md`](SAFETY.md)
- **All phases:** [Course map](#course-map)

> Markdown navigation links work on GitHub and in most Markdown editors. To record progress, edit the tracker and change `- [ ]` to `- [x]`, then save or commit the change. GitHub does not automatically save your personal progress just because you read a page.

## Course map

| Phase | Topic | Open lesson |
|---|---|---|
| 0 | Check your setup | [Start here](phases/00-setup.md) |
| 1 | Linux basics | [Open Phase 1](phases/01-linux-basics.md) |
| 2 | Processes, services and logs | [Open Phase 2](phases/02-processes-and-logs.md) |
| 3 | Discover hardware and serial devices | [Open Phase 3](phases/03-hardware-discovery.md) |
| 4 | Python environments and serial I/O | [Open Phase 4](phases/04-python-serial.md) |
| 5 | C programming on Linux | [Open Phase 5](phases/05-c-on-linux.md) |
| 6 | Sensor interfaces: UART, I²C and SPI | [Open Phase 6](phases/06-sensor-interfaces.md) |
| 7 | Build a telemetry logger | [Open Phase 7](phases/07-telemetry-logger.md) |
| 8 | Reliability and a systemd service | [Open Phase 8](phases/08-service-reliability.md) |
| 9 | Microcontroller-to-Pi bridge | [Open Phase 9](phases/09-microcontroller-bridge.md) |
| 10 | Portfolio project | [Open Phase 10](phases/10-portfolio.md) |

## How to use this course

1. Open the current phase from the table.
2. Work through **Learn**, **Try it**, and **Checkpoint** in order.
3. Tick the matching item in [the progress tracker](progress/TRACKER.md).
4. Write what worked, what failed, and the next action in [your learning journal](progress/LEARNING_LOG.md).
5. Use the **Next phase →** link at the bottom when you pass the checkpoint.

## Progress at a glance

The tracker is the source of truth. Keep it updated as you go. A suggested rule: **do not move to the next phase until you can explain the checkpoint in your own words**, even if you needed to look up commands.

## Your destination

Build a **Modular Sensor Telemetry Unit**:
- Raspberry Pi collects measurements from a sensor, GNSS receiver, serial device, or simulator.
- A Python application validates and timestamps readings.
- Data is stored in CSV first, then SQLite.
- The program handles malformed, missing, and stale data.
- Later, a microcontroller can send structured packets to the Pi over UART.
- The project has setup instructions, tests, sample data, and a short demo.

**Next:** [Phase 0 — Check your setup](phases/00-setup.md)
