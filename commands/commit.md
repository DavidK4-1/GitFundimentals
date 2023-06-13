# git commit 
the command `git commit` will take all tacked changes (items added with [git add](./add.md)) and package them up in what is called a commit

commits come with commit messages that are required for each commit. you add a message to a commit by using the `-m` flag followed by a message in quotes

a commit message _can_ be anything, but best practice dictates that you should use that message to indicate the changes included in the commit

for example, if we have an application we're working on whare we just built out the ability to register new accounts, than you might have some variation of the following:

```
git add .
git commit -m "added register functionality"
```

then when viewing the history of git repository, you can pinpoint whare the registration functionality was added

## resources
- [git commit documentation](https://git-scm.com/docs/git-commit)
---

[back to home](../README.md)