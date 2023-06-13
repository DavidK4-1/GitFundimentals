# git remote

when working with git, a **remote** is any git repository that is not on the machine you are working on. Tht counterpart is **local**, or the machine it was developed on

take GitHub for example. While git is the technology thta allows you to create local repositories, GitHub is the sight that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others

### adding a remote

a remote can be added with the `git remote add` command, followed by the name and location of the remote.

the name it a local name, meaning it's your label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/ELEVENFIFTYACADEMY/gitFundimentals.git
```

### removing a remote

a remote can be removed with the `git remote remove` command, followed by the name of the remote

```
git remote remove origin
```

## resources

- [git remote documentation](https://git-scm.com/docs/git-remote)

[back to home](../README.md)