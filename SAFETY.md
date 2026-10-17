# Hardware and data safety

[← Back to dashboard](README.md)

- Raspberry Pi GPIO uses **3.3 V logic** and is not 5 V tolerant. Check the exact board documentation before wiring.
- Disconnect power before changing wiring.
- Do not power motors, servos, radios, or other high-current loads from GPIO pins.
- Check voltage levels, pinouts, and common ground before connecting devices.
- Begin with read-only hardware discovery. Do not test new code on a live aircraft or flight-critical system.
- Back up files before changing OS, partitions, boot configuration, or network settings.
- Never commit passwords, API tokens, SSH private keys, Wi-Fi credentials, or private GNSS/location logs to a public repository.
- `.gitignore` helps, but it does **not** guarantee that sensitive files will never be committed.
- If a command is unfamiliar, understand what it changes before running it with `sudo`.

## Safe working pattern

1. Identify the exact board/device.
2. Read its pinout and voltage requirements.
3. Test one interface at a time.
4. Record the command and result in your learning journal.
5. If something behaves unexpectedly, stop and disconnect power before inspecting wiring.
