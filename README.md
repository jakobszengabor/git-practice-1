# Introduction

In this task, you will learn how to properly prepare branches for merge requests (MRs) in Git. Follow the steps below to practice forking, branching, merging, and squashing commits. Additionally, create a **.txt** file in your repository to document the commands you run during the process.

## Prepare Branches

- fork this repository
- clone it to your local machine
- make a `develop` branch from `main`
- add `.gitignore` file to `develop` and upload it to remote
- create `f1` branch from `develop`
  - add `index.html` file with some content and commit it with `f1: index.html` message
  - add `styles.css` file with some content and commit it with `f1: styles.css` message
  - add `index.js` file and commit it with `f1: index.js` message
  - squash these three commits into one.
- create `f2` branch from `develop` branch
  - add `LICENSE` file with `MIT` License text and commit
  - push `f2` branch to remote
  - merge `f2` branch into `develop` (do not delete branch on remote)
  - update remote `develop` branch (remote and local)
- update `f1` branch from `develop` (merge or rebase)
- squash commits in `f1` branch. (the main goal to have one commit before MR)
- make MR from `f1` to `develop` branch
- attach a link or your repo to the assignment

`Important don't delete branches after merge`

### Useful links

- [License](https://en.wikipedia.org/wiki/MIT_License)
- [Git squash 1](https://www.w3docs.com/snippets/git/how-to-combine-multiple-commits-into-one-with-3-steps.html)
- [Git squash 2](https://www.youtube.com/watch?v=V5KrD7CmO4o&ab_channel=TheModernCoder)
- [Merge](https://www.atlassian.com/git/tutorials/using-branches/git-merge)
- [Rebase](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)
- [Merge vs Rebase](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)