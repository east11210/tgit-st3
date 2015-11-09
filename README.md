tgit-st3
========

TortoiseGit Plugin for Sublime Text 3

A simple plugin to expose the best of the TortoiseGit GUI to the 
Sublime Text 3 context menu.

Adds the following to the context menu for an active file:

* Diff
* Show log
* Commit
* Sync

If there is no active file, it tries to guess the "relevant" repository
by looking at the project file or the first open folder.