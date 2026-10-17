# Phase 1 — Linux Basics

[← Dashboard](../README.md) | [← Previous: Setup](00-setup.md) | [Progress tracker](../progress/TRACKER.md) | [Next phase →](02-processes-and-logs.md)

## Goal

Become comfortable moving around the filesystem and manipulating files without fear. This is the foundation for embedded Linux work.

## 1. Learn the core commands

| Command | Purpose |
|---|---|
| `pwd` | Show the current directory |
| `ls -la` | List files, including hidden files |
| `cd path` | Change directory |
| `mkdir name` | Create a directory |
| `touch file.txt` | Create an empty file or update its timestamp |
| `cp source destination` | Copy a file |
| `mv source destination` | Move or rename a file |
| `cat file.txt` | Print a small text file |
| `less file.txt` | Read a longer file |
| `file filename` | Identify a file type |
| `man command` | Read the manual, when available |

## 2. Try it yourself

Run these commands one at a time:

```bash
cd ~/embedded-telemetry
pwd
mkdir phase1-practice
cd phase1-practice
touch notes.txt
echo "My first Linux practice file" > notes.txt
cat notes.txt
cp notes.txt notes-copy.txt
mv notes-copy.txt backup.txt
ls -la
file notes.txt
```

Expected result: `notes.txt` and `backup.txt` exist, and `cat notes.txt` displays your sentence.

## 3. Understand paths

- An **absolute path** starts at `/`, for example `/home/pi/embedded-telemetry`.
- A **relative path** is interpreted from your current directory, for example `phase1-practice/notes.txt`.
- `.` means the current directory; `..` means the parent directory.
- `~` means your home directory.

Try:

```bash
pwd
cd ..
pwd
cd -
pwd
```

`cd -` normally returns you to the previous working directory.

## 4. Get help instead of guessing

Try:

```bash
ls --help
man ls
```

Press `q` to leave `man` or `less`.

## Exercise

Without copying the sequence above, create `phase1-practice/results/summary.txt` and put one sentence inside it. Then display the file and list its parent directory.

Hints: use `mkdir -p`, `echo`, `cat`, and `ls`.

## Checkpoint — explain it in your own words

- [ ] I can tell where I am with `pwd`.
- [ ] I can list hidden files with `ls -la`.
- [ ] I can explain absolute vs relative paths.
- [ ] I can create, copy, move, and read files.
- [ ] I completed the exercise without blindly pasting the whole solution.

Record one thing that confused you in the [learning journal](../progress/LEARNING_LOG.md). Tick Phase 1 in the [tracker](../progress/TRACKER.md) only when you can do the tasks again.

**Next phase:** [Phase 2 — Processes, Services and Logs](02-processes-and-logs.md)
