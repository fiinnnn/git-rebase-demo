# git-rebase-demo
Example repo to demonstrate git rebase usage

Contains a `main` and `feature` branch with the best code ever.

## Usage

Rebase feature onto main:
```
> git rebase main feature
// OR
> git checkout feature; git rebase main
```

Interactive rebase:
```
> git checkout feature
> git rebase -i main
```
