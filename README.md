# Ahmed Dev Toolkit

A macOS developer maintenance CLI — interactive terminal menu for cleaning caches, managing disk space, and keeping your dev environment healthy.

Built for Apple Silicon (M1/M2/M3/M4) Macs with a full development stack.

---

## Features

| # | Option |
|---|--------|
| 1 | System Information — macOS version, CPU, RAM, disk, installed tools |
| 2 | Disk Usage Report — top space consumers + key cache sizes |
| 3 | Homebrew Cleanup — removes old bottles and unused dependencies |
| 4 | npm / pnpm / yarn / PHP / Composer Cleanup — clears all package manager caches |
| 5 | Docker Cleanup — prunes images, containers, volumes, build cache |
| 6 | VS Code Cache Cleanup — clears VS Code cache and logs |
| 7 | System Cache Cleanup (Safe) — user-level caches only, Apple folders skipped |
| 8 | Flush DNS Cache — clears macOS DNS resolver cache |
| 9 | Empty Trash — permanently deletes trash contents |
| 10 | Find Large Files — scans home directory for files over 500 MB |
| 11 | Developer Deep Clean — runs all cleanups in one shot |
| 12 | Update Everything — updates Homebrew, npm globals, AWS CLI |
| 13 | Health Report — disk usage, cache sizes, brew doctor |
| 14 | View Cleanup Log — shows history of all cleanup actions |

---

## Requirements

- macOS (Apple Silicon recommended)
- [Homebrew](https://brew.sh) installed

---

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/Ahmed-React-JS/devtool/main/devtool -o devtool && chmod +x devtool && sudo mv devtool /usr/local/bin/devtool
```

---

## Run

```bash
devtool
```

---

## Update

When a new version is released, just re-run the install command:

```bash
curl -fsSL https://raw.githubusercontent.com/Ahmed-React-JS/devtool/main/devtool -o devtool && chmod +x devtool && sudo mv devtool /usr/local/bin/devtool
```

---

## Cleanup Log

Every action is logged to `~/.devtool-log.txt`. View it anytime from option 14 in the menu.
