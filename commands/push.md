# git push

when you have a [remote](./remote.md) set up you'll need to begin to move [commits](./commit.md) to the remote. this can be done with the command `git push`

you can attatch a name and branch name to your command to specify where you 're pushing to

```
git push origin main
```
this command will push the **main** branch to the remote called **origin**

### upstream tracking

instaid of including the name of the remote and the branch you're on every time, you can set local branches to track an upstream branch. this means you can tell the branch to push the assigned upstream remote branch by using the command `git push`.

before doing so, you'll need to use the `-u` or `--set-upstream` flag. this can be done on any `git push`.

```
git push -u origin main
```

## resources
- [git push documentation](https://git-scm.com/docs/git-push)
---

[back to home](../README.md)