# A03

Git - a distributed version-control system for tracking changes in source code during software development.
GitHub - a web-based version-control and collaboration platform for software developers that uses Git.
Repository - the most basic element of GitHub. They're easiest to imagine as a project's folder.  A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.
Clone - a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. With your clone you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. It is, however, connected to the remote version so that changes can be synced between the two. You can push your local changes to the remote to keep them synced when you're online.
Commit - or "revision", is an individual change to a file (or set of files). It's like when you save a file, except with Git, every time you save it creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of what changes were made when and by who. Commits usually contain a commit message which is a brief description of what changes were made.
Push - refers to sending your committed changes to a remote repository, such as a repository hosted on GitHub. For instance, if you change something locally, you'd want to then push those changes so that others may access them.
Pull -  refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date.
Branch - a parallel version of a repository. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the master branch to publish your changes. For more information, see "About branches."
Merge -  takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a pull request (which can be thought of as a request to merge), or via the command line. A merge can be done automatically via a pull request via the GitHub web interface if there are no conflicting changes, or can always be done via the command line. For more information, see "Merging a pull request."
Merge Conflict - problems when merging during a pull request when files don't match.
Fetch - refers to getting the latest changes from an online repository without merging them in. Once these changes are fetched you can compare them to your local branches (the code residing on your local machine).
Remote - the version of something that is hosted on a server, most likely GitHub. It can be connected to local clones so that changes can be synced.

My Knowledge of GitHub:

To use GitHub in the most simplistic way possible, use the user interface.
To create a new repository, click new in the left-hand section where repositories are listed.
To upload files in a repository, go to the repository, click the "upload files" link, then drag and drop them or choose to click "choose your files".


Commits should have clear messages like:

Task: Create Repository
Feature:  added workflow for using github
Fix:  changed readme.md for definition of terms


REFERENCES FOR DEFINITIONS: https://help.github.com/en/articles/github-glossary and Google definitions
