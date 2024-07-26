# **Useful info about GIT**
The *git reset*, *git checkout*, and *git revert* commands are some of the most useful tools in your Git toolbox.
## **Git revert**
A revert operation will take the specified commit, inverse the changes from that commit, and create a new "revert commit". The ref pointers are then updated to point at the new revert commit making it the tip of the branch.
It's important to understand that git revert undoes a single commit—it does not "revert" back to the previous state of a project by removing all subsequent commits. In Git, this is actually called a reset, not a revert.
## **Git reset**
The git reset command is a complex and versatile tool for undoing changes. It has three primary forms of invocation, correspond to command line arguments --soft, --mixed, --hard.
Git reset, moves both the HEAD and branch refs to the specified commit.
The ref pointer modification always happens and is an update to the third tree, the Commit tree. 
## **Git checkout**
The git checkout command operates upon three distinct entities: files, commits, and branches.

# **GUI Clients to work with GIT**
There are several great GUI clients available for working with Git that can make version control easier and more intuitive. Here are some popular options:

1. **GitHub Desktop**: A user-friendly client that integrates seamlessly with GitHub, making it easy to manage repositories, branches, and commits.

2. **Sourcetree**: A free Git client from Atlassian that provides a visual interface for managing repositories, branches, and merges. It supports both Git and Mercurial.

3. **GitKraken**: A powerful and visually appealing Git client that offers a unique interface and features like a built-in code editor and issue tracking integration.

4. **Fork**: A fast and friendly Git client for both Mac and Windows, Fork offers a clean interface and features like a commit history graph and interactive rebase.

5. **SmartGit**: A cross-platform Git client that provides a comprehensive set of features for managing repositories, including support for GitHub, Bitbucket, and GitLab.

6. **TortoiseGit**: A Windows shell interface for Git that integrates with Windows Explorer, allowing you to manage your repositories directly from the file system.

7. **GitUp**: A Git client for macOS that focuses on speed and simplicity, providing a live visual representation of your repository.

Each of these clients has its own strengths, so you might want to try a few to see which one fits your workflow best! If you have any specific needs or preferences, feel free to ask!

