# Intro to Git

## Version Control (VCS)

Version Control is a system that allows you to revisit various versions of a file, or set of files, by recording changes. With version control,
you can change a file back to a previous version, track modifications and compare any changes. 

### Centralized Version Control System (CVCS)

This is a server that stores all changes and file versions, which then can be accessed by different users. 
This allows programmers to keep tabs on what their team is working on.

### Distributed Version Control System (DVCS) 

The DVCS addresses some issues with the CVS. For example, if CVS goes down, team members can't work with each other on a file or make new edits to it. 
If there is no backup, all the work will be lost, unless it's saved on a local machine. To prevent this from happening, a DVCS lets clients create mirrored repositories.

### What is Git?

Git is comprised of snapshots. It is a DVCS that stores data in a file system made up of snapshots. When you save your project, called commit, Git creates a snapshot 
of the file and stores a reference to it. Git usually relies on local operations found in local resources. This lets you continue working on a project even when you're not 
online or on a VPN. All changes made to a file or directory is tracked by Git. Git will also detect file corruption or any loss of information. 

### Files in Git come in 3 states: committed, modified, and staged.

1. Committed-data is securely stored in a local database
2. Modified-a file can be changed but not committed to the database
3. Staged-flagged a file's changed version to be committed in the next snapshot

### History of Git

Git started with a project called Linux kernel, which was an open source project.
Developers used a DVCS called Bitkeeper in 2002. The creator of Linux Kernel, Linus Torvalds, also created Git and Git has been widely used since 2005. 
Git comes with Graphical User Interface(GUI) tools.

### Cloning

You can clone, or create a copy, of a Git repository by using the clone command
with your repository's URL. When you clone a file, you have all the versions.
A local Git repository has three components:

1. Working Directory: The files reside here
2. Index: THe area used for staging
3. Head: Points to the most recent commit 

### Saving Changes 

All files that are in a project file are either in a track or untracked state.
Tracked files can be modified, unmodieifed or staged. Untracked files weren't
in the last snapshot. After you edit a file, Git marks it as modified. 
After you modify a file, you'll need to commit the changes. Then you can
check the status with 'git status'. 

### ACP

To get a repository onto your computer, you use ACP(add, commit, push).
To add a single file: git add filename
To add all files in a repository: git add *
To commit a file: git commit -m "your file description"
To push a file: git push origin main 
