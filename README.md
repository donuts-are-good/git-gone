# git-gone
purge a file from your git history

## What?

Have you ever accidentally commited a file to a Git repo that wasn't supposed to be there? This tool removes that file from your Git history. For me, it's because I keep committing nonsense files that the OS on this computer generates for my folders.

## How?

The tool doesn't do anything special, and the script is commented so that it can be understood and extended. Git already provides a way to do this, but I can't remember the long command and sequences for all of that half the time when I need it, so here we are making a tool for it.

## Example:

Oh now, we've committed TODO.txt in our Git project and we want it gone! The solution is simple:

```
git-gone TODO.txt
```

Any unstaged changes will be stashed (with instructions to restore them) and any remnants of TODO.txt will be purged from the history, which gets pushed immediately. 

## TODO.txt

- Apply for VC funding
- git-gone-token - 100% premine
- 
- profit