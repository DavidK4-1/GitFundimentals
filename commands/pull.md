# git pull

similar to a [git push](./push.md), a `git pull` will interact with a remote repository. Only this time it will **pull** the changes it does not have from the remote down to the local repository

this means that commits made that are on the remote repository will be pulled down and added to the local repository

this can be done by adding the remote name and branch name:

```
git pull origin main
```

if there is any upstream connection established, you can use the `git pull` without specifying the remote or branch

## resources
- [git pull documentation](https://gitscm.com/docs/git-pull)
---

[back to home](../README.md)