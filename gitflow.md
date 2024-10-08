## Gitflow Workflow

This version control method is a more modern approach to handling large projects in an efficient manner. It involves using different **feature branches** and  **multiple primary branches** which all have their specific roles. Compared to *Feature Branch Workflow* which uses one central branch (e.g. main) this branching strategy allows for more structured and robust way for introducing scheduled large updates and patches.  

***

<img src="image.png" alt="Gitflow Workflow">

*Source: Driessen, V., [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)*

***

### Main branch

- This branch stores an **official release history**. 
- The commits to this branch are not frequent and tend to be tagged with their specific versions.
- New commits are either hotfixing bugs or introducing new major updates 
- **Goal** - allows having a stable version of a project

***

### Develop branch

- **Main contribution of this branching strategy**
- This branch serves as **an integration place for features**
- Feature branches are merged into this branch creating a preliminary version of an updated project
- **Goal** - serves a role of accumulating feautures and preparing projects before release

***

### Feature branches

- Work in similar manner as in *Feature Branch Workflow*
- Forked from develop branch and upon finishing are merged back into it
- **Goal** - playing ground for developers for safe experimenting with new feautures

***

### Release branch(es)
- This branch is used to **prepare a new version of a project for release**
- It is **forked from developed** and subsequently **merged into main**
- On this branch no new features are introduced and only bug fixes and similar things are added
- **Goal** - serves a role of a final preparation and refining of a new of version of a project

***

### Hotfix branches
- **Quickly patch production releases**
- It is **forked from main** and after a fix merged back into it
- **Goal** - serves a quick and simple way to hotfix a project

***



