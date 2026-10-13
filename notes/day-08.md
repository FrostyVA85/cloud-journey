# Day 8 - Git: the daily routine

## Start of a session
1. `git status` - how did I leave things?

## After each piece of work
1. `git status` - what changed?
2. `git diff` - is it what I meant?
3. `git add <file>` or `git add .`
4. `git commit -m "what the change does"`
5. `git push`

## End of a session
- `git status` says "up to date" and "nothing to commit"

## Rules
- `.gitignore` lists what Git must leave alone
- Secrets never go into a repository
- If a secret is committed: change the secret first