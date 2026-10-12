# Day 4 - What the operating system is doing

## Ideas
- A **program** is a file
- A **process** is a program that is running
- Every process has a number, which is its **ID** (PID)
- A **service** runs in the background with no window
- The pipe `|` hands the result of one command to the next

## Commands
- `ps` = list processes
- `ps | sort WA -Descending | select -First 5` = the five using most memory
- `kill 1234` = stop the process with that ID
- Ctrl + C = stop the command running in my terminal
- `Get-Service` = list services
- `systeminfo | findstr Memory` = memory total and free
- `Get-PSDrive C` = disk used and free on the C drive

## My computer right now
- Processes running: 305
- Services running: 307
- Memory available: 48.248 MB
- Disk free: 376.07 GB