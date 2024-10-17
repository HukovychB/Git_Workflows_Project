# Git_Workflows_Project
This is the final project for the course Version Control with Git

---

### Centralized Workflow

The Centralized Workflow uses a central repository to serve as the single point of entry for all changes to the project. The default development branch is called main, and all changes are committed into this branch. This workflow doesn’t require any other branches besides main. 

The Centralized Workflow is like other workflows in its utilization of a remote server-side hosted repository that developers push and pull from. Compared to other workflows, the Centralized Workflow has no defined pull request or forking patterns. A Centralized Workflow is generally better suited for smaller size teams.
---

## Workflow from the perspective of a single developer

- Clone the master branch of remote repository
- Commit any changes to the local repository
- Push changes (a set of commits) to the central repository
- (If needed) resolve a conflict
- Push changes to central repository 

## Advantages and disadvantages of Centralized Workflow

The advantage of the Centralized Workflow is that there is only a small shift in how to think about your code and the repository. The team does not have to learn a completely new way and approach to using version control. The drawback to this workflow is that your master branch is always at risk of being broken by code changes. The other approaches we discuss address that.

## Summary

We summarized here **4 popular version control workflows**. 

1. **Centralized Workflow** - A single central repository is used, and all changes are committed directly to it.

2. **Feature Branch Workflow** - Each new feature is developed in its own branch, which is merged back into the main branch once complete.

3. **Gitflow Workflow** - A more complex workflow that uses multiple branches for feature development, releases, and hotfixes to manage the project lifecycle.

4. **Forking Workflow** - Developers create their own fork of the repository, make changes, and then submit pull requests to the original repository for review and integration.

Each of these workflows can be tailored to fit different project requirements and team structures. By understanding the advantages of each workflow, teams can select the one that best aligns with their *development practices* and *project goals*, *ensuring efficient and organized collaboration*.
