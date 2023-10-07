# Git  

- [Branch & Merge](#branch--merge)
- [Init](#init) 
- [Path Changes](#path-changes)
- [Setup](#setup)
- [Share & Update](#share--update)
- [Stage & Snapshot](#stage--snapshot)

## Branch & Merge 
| Command                                   | Result                                                                        |
|-------------------------------------------|-------------------------------------------------------------------------------|
| `git branch`                              | List your branches. A * will appear next to the currently active bracnch      |
| `git branch [branch-name]`                | Create a new branch at the current commit                                     |
| `git checkout`                            | Switch to another branch and check it out into your working directory         |
| `git merge [branch]`                      | Merge the the specified branch's history into the current one                 |
| `git log`                                 | Show all commits in the current branch's history                              |

## Init  
| Command                                   | Result                                                                |
|-------------------------------------------|-----------------------------------------------------------------------|
| `git init`                                | Initialize existing directory as Git repository                       |
| `git clone [url]`                         | Retrieve an entire repository from a hosted location via URL          |

## Ignore Patterns
| Command                                                | Result                                                                |
|--------------------------------------------------------|-----------------------------------------------------------------------|
| `git config` --global core.excludesfile [file]         | System wide ignore pattern for all local repositories                 |

## Path Changes
| Command                                   | Result                                                                |
|-------------------------------------------|-----------------------------------------------------------------------|
| `git rm [file]`                           | Delete the file from project and stage the removal for commit         |
| `git mv [existing-path][new-path]`        | Change an existing file path and stage the move                       |
| `git log --stat M`                        | Show all commit logs with inidcaiton of any paths moved               |

## Rewrite History
| Command                                   | Result                                                                |
|-------------------------------------------|-----------------------------------------------------------------------|
| `git rebase [branch]`                     | Apply any commits of current branch ahead of specified one            |
| `git reset --hard [commit]`               | Clear staging area, rewrite workign tree from specified commit        |

## Setup  
| Command                                   | Result                                                                |
|-------------------------------------------|-----------------------------------------------------------------------|
| `git config --global user.name`           | Configure user username across all local repositories                 |
| `git config --global user.email`          | Configure user email across all local repositories                    |
| `git config --global color.ui auto`       | Set automatic command line coloring for Git                           |

## Share & Update
| Command                                   | Result                                                                |
|-------------------------------------------|-----------------------------------------------------------------------|
| `git remote add [alias] [url]`            | Add a git URL as an alias                                             |
| `git fetch [alias]`                       | Fetch down all the branches from that Git remote                      |
| `git merge [alias]/[branch]`              | Merge a remote branch into your current branch to bring it up to date |
| `git push [alias] [branch]`               | Transmit local branch commits to the remote repository branch         |
| `git pull`                                | Fetch and merge any commits from the tracking remote branch           |

## Stage & Snapshot 
| Command                                   | Result                                                                |
|-------------------------------------------|-----------------------------------------------------------------------|
| `git status`                              | Show modified files in working directory, staged for your next commit |
| `git add [file]`                          | Add a file as it looks now to your next commit (stage)                |
| `git reset [file]`                        | Unstage a file while retaining the changes in working directory       |
| `git diff`                                | Diff of what is changed but not staged                                |
| `git diff --staged`                       | Diff of what is staged but not yet committed                          |
| `git commit -m '[descriptive message]`    | Commit your staged content as a new commit snapshot                   |

## Temporary Commits
| Command                                   | Result                                                                |
|-------------------------------------------|-----------------------------------------------------------------------|
| `git stash`                               | Save modified and staged changes                                      |
| `git stash list`                          | List stack-order fo stashed file changes                              |
| `git stash pop`                           | Write working from top of stash stack                                 |
| `git stash drop`                          | Discard the changes from the top of stash stack                       |
