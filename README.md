# space-manage
# Automated Log & Directory Cleaner (Bash)

## Project Goal
An automated Bash script that recursively scans target project folders, identifies stale build artifacts and old log files based on configurable age thresholds, and safely previews or purges them to recover local disk space.

## Tech Stack
* **Language:** Bash Shell Scripting
* **Utilities:** `find`, `du`, `awk`, `rm`, `getopts`, `cron`
* **Storage:** Plain text configuration (`cleaner.conf`) and execution log (`cleaner.log`)

## Project Structure
```text
log-cleaner-bash/
├── config/       # Default configurations (cleaner.conf)
├── docs/         # Eisenhower Matrix & System Diagram
├── logs/         # Execution history (cleaner.log)
├── src/          # Shell scripts (cleaner.sh)
├── .gitignore
└── README.md
