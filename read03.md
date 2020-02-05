# Read: 03 - Revisions and the Cloud
## A little about Git 

*So, what is Git?* :
* Snapshots

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

* Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

* Tracking Changes

* Loss of Data:

Git  reduce the possibility of irreversible damage to files . 

* States:

Files in Git can reside in three main states: committed, modified and staged.

1. Committed
Data is securely stored in a local database

2. Modified
File has been changed but not committed to the database

3. Staged
Flagged a file’s changed version to be committed in the next snapshot

## Getting Started
1. first download Git, 
Git can be installed in three ways:

* Install as a package
* Install via another installer
* Download and compile the source code.

## Initial Customization
1. Configuration of Variables
An inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.

2. dentity Setting
After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.

Type the following into Terminal or Command Line:
git config --global user.name "github-username"
git config --global user.email "egithub-email"


## Check Settings
To check settings, use the git config --list command.

## Setting up a Git Repository:
1. Switch to the target project’s directory(using cd command).
2. Use the (git init command). 
3. To start tracking these repository files, perform an initial commit by typing the following:
* $ git add *.c

* $ git add LICENSE 
* $ git commit -m “any message here”

## Cloning
 use the command ($ git clone https://github.com/test mydirectory)
 





