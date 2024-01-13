# MiracleAnyiam

**VERSION CONTROL**

*Version control is a system that tracks changes to a project's files over time, allowing multiple contributors to collaborate on the same codebase. It helps manage revisions, enables easy collaboration, and provides a history of changes. Popular systems include Git and SVN.*

**DIFFERENCE BETWEEN GIT AND GITHUB**

**Git** *is a distributed version control system, while GitHub is a web-based platform that utilizes Git for version control. Git is the tool you use locally to manage source code history, whereas **GitHub** serves as a remote repository hosting service, facilitating collaboration and providing additional features like issue tracking and pull requests.*

**OTHER GITHUB ALTERNATIVES**

- GitLab
- Azure DevOps
- Bitbucket

**DIFFERENCE BETWEEN GIT FETCH AND GIT PULL**

**git fetch** *retrieves changes from a remote repository, updating your local copy of the remote branches, but it doesn't automatically merge them into your working branch. It's useful for reviewing changes before deciding to merge.*

*On the other hand, **git pull** not only fetches changes from the remote repository but also automatically merges them into your current working branch. It's a combination of **git fetch** and **git merge**, providing a more streamlined approach for pulling and integrating changes.*

**GIT REBASE**

*In simple terms, **git rebase** is like rewriting the history of your changes to make it look cleaner and more linear. It helps integrate your changes with the latest updates from the main branch.*

The command for interactive rebase is:
- git rebase (base_branch)

**GIT CHERRY-PICK**

*In simple terms, **git cherry-pick** lets you pick and apply specific commits from one branch and add them to another branch. It's like choosing certain changes and adding them to your current work.*

The command for cherry-pick is:
- git cherry-pick (commit-hash)
