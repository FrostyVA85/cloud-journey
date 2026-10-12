# Day 6 - Git: keeping a history

## Ideas
- A repository is a folder that Git is tracking
- A commit is a snapshot of my files, with a message

## The cycle
1. Edit and save
2. `git status` - what has changed?
3. `git add <file>` - choose what goes in the snapshot
4. `git commit -m "message"` - take the snapshot

## Looking Back
- `git log --oneline` = the list of commits
- `git diff` = what I changed since the last commit
- `git restore <file>` = throw away uncommited changes