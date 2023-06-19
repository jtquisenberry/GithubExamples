# Change Origin

After installing from a branch, git may not be able to checkout branches other than the one installed. To resolve this issue, remove the reference to origin and create a new link. This will break the relationship between the local branch and the remote branch. Use --set-upstream-to to establish a relationship between the local and remote branches.

In this example, `branch1` is a local branch and `origin/branch1` is a remote branch.

```
git remote
git remote remove origin
git remote add origin https://github.com/jtquisenberry/GithubExamples.git
git fetch
git branch --set-upstream-to=origin/branch1 branch1
git checkout main
```
