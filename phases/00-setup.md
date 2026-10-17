# Phase 0 — Check your setup

[← Dashboard](../README.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](01-linux-basics.md)

## Goal

Confirm what system you are working on and create a safe workspace. These commands inspect the system; they should not change its configuration.

## 1. Run the system inventory

Run each command in your Pi terminal:

```bash
cat /etc/os-release
uname -r
lscpu
free -h
lsblk
```

If a command is unavailable, record that rather than installing random packages immediately.

## 2. Create a workspace

```bash
mkdir -p ~/embedded-telemetry/{notes,scripts,data,logs}
cd ~/embedded-telemetry
pwd
ls -la
```

## 3. Record your environment

Write the OS, kernel, storage, and any hardware currently attached in your [learning journal](../progress/LEARNING_LOG.md). Do not publish serial numbers or private location data.

## Checkpoint

- [ ] I know which OS and kernel I am running.
- [ ] I can find my workspace.
- [ ] I have recorded my setup.

When complete, update the [progress tracker](../progress/TRACKER.md), then continue to [Phase 1 — Linux Basics](01-linux-basics.md).
