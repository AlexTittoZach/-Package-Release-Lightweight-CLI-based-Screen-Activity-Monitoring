# ScreenTracker

A lightweight, privacy-first screen activity tracker for Windows.
Track application usage, coding time, productivity, idle time, and daily activity patterns directly on your machine.

## Features

- Real-time application tracking
- Automatic idle time detection
- Productivity score calculation
- Coding time tracking
- Top applications and activities
- Hourly activity heatmap
- Local SQLite database storage
- Single-instance protection
- Fully offline and privacy-friendly

## Installation

Simply install the release package file and run ``` screentracker ``` that's it

## OR

Clone the repository:
```bash
git clone https://github.com/AlexTittoZach/Lightweight-CLI-based-Screen-Activity-Monitoring.git
cd Lightweight-CLI-based-Screen-Activity-Monitoring
```
Install the package:
```bash
pip install .
```
Start ScreenTracker by:
```bash
python -m screentracker.tracker
```

## Data Storage

All data is stored locally:

```text
C:\Users\<username>\AppData\Local\ScreenTracker
```

Files:
```text
usage.db
tracker.lock
```

## Privacy

ScreenTracker works completely offline.
- No cloud storage, no user accounts, no external APIs, no data leaves your computer
- Works silently in terminal

## Requirements

- Windows 10 / 11
- Python 3.10+

## Tech Stack

- Python
- SQLite
- Rich
- psutil
- pywin32
  
## Author - Alex Titto Zacharias
