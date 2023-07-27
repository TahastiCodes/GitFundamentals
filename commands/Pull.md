# git pull

Similar to `git push`, a `git pull` will interact with a remote repository. Only this time it will **pull** the changes it does not have from the remote down to the local repository.

This means any commits made that are on the remote repository will be pulled down and added to the local repository.

This can be done by adding the name and branch name:
```
git pull origin main
```

If there is an upstream connection established, yu can use `git pull` without specifying a remote or branch.

## Resources

- [Git Pull Documentation](https://git-scm.com/docs/git-pull)

---
[Back to home](../README.MD)