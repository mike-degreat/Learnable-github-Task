# Learnable-github-Task

## 1. Explain Version control

Version control also known as source control is like a magical notebook that remembers everything. It keeps track of every change you make, along with who made it and when. You can rewind to any previous version, compare difference and even merge different versions together.

Think of it as a time machine for your files. Whether its code, documents, images or any other files, version control lets you:

> **Get back in time:** >_Imagine you made a mistake, with version control you can revert back to any previous version._

> **See the evolution:** _With version control you can trace the changes made over time_

> **Work together seamlessly:** _Collaborate with others without overwriting each other's work_

> **Experiment freely:** _Try out new ideas without ruining the original version_

## 2. Explain the difference between git and github

| **Git**                                                             | **Github**                                                                    |
| ------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| _Software(Version control system)._                                 | _Web-based service._                                                          |
| _Tracks changes in files over time._                                | _Hosts Git repositories and provides collaboration features._                 |
| _Distributed (stores copies on each user's device)._                | _Centralized (stores one copy in the cloud)._                                 |
| _No built-in user management._                                      | _Has user profiles and accounts._                                             |
| _Open-source and free to use._                                      | _Free basic plan, paid plans for advanced features and private repositories._ |
| _Commit changes, track history, merge branches, resolve conflicts._ | _Manage Git repositories, collaborate with others, review code, track bugs._  |
| _Can be used offline._                                              | _Requires internet connection_                                                |
| _Steeper, requires command-line knowledge_                          | _Easier to use, visual interface and collaboration tools_                     |

## 3. List 3 other alternatives to github

- Gitlab
- Bitbucket
- Gitea

## 4. Explain the difference between `git fetch` and `git pull`

| **Git Fetch**                                         | **Git pull**                                 |
| ----------------------------------------------------- | -------------------------------------------- |
| _git fetch downloads updates but doesn't merge them._ | _git pull fetches updates and merges them._  |
| _git fetch is used to review changes before merging_  | _updates local branch with lastest changes._ |
| _Doesn't affect working directory._                   | _Affects working dirctory._                  |

## 5. Explain in simple terms `git rebase` and the command for it

**Git Rebase**
: git rebase is a Git command used for integrating changes from one branch into another while maintaining a cleaner and more linear commit history.

**Git Rebase Command**
: `git rebase <base-branch>`

## 6. Explain in simple terms `git cherry-pick` and the command for it

**Git cherry-pick**
: git cherry-pick is a Git command that allows you to pick and apply specific commits from one branch and apply them onto another branch. It's like selecting specific changes and copying them to a different branch.

**Git cherry-pick command:**
`git cherry-pick <commit-hash>`
