# Git & GitHub Cheat Sheet

The commands that cover almost everything you'll do this semester.

## One-time setup
```
git config --global user.name  "Your Name"
git config --global user.email "ID+username@users.noreply.github.com"
```

## Get a repo onto your machine
```
git clone <url>          # download a repo you own or forked
```

## The everyday loop
```
git status               # what have I changed?
git add <file>           # stage a file   (git add .  stages everything)
git commit -m "message"  # save a snapshot with a note
git push                 # send your commits to GitHub
```

## Stay up to date with the S617 repo
```
git pull                 # get the latest from your own fork
git pull upstream main   # get new labs from the S617 repo
```

## Handy
```
git log --oneline        # see your history
git diff                 # see exactly what changed
git branch <name>        # (later) work without touching main
```

## Rules of thumb
- Commit small and often, with messages that say *what* and *why*.
- Never `git add` a file with a password, key, or `.env` in it.
- Unsure? Run `git status` - it almost always tells you what to do next.
