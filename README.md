## Quick and useful commands for a quick-beginner.
### Following are the summary of commands what I learnt as github beginner

## Useful links 
https://help.github.com/articles/create-a-repo/

https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository

Quickest-way to learn
https://try.github.io/levels/1/challenges/1

### create a directory in local computer
`mkdir github_test`

`cd github_test`

### Initialise the git repository
`git init`

### check the status
`git status`

### create files
`touch a.txt b.txt`
`git status`

### add the new created files
`git add a.txt b.txt`

### Committing
Notice how Git says changes to be committed? The files listed here are in the Staging Area, and they are not in our repository yet. We could add or remove files from the stage before we store them in the repository.

`git commit -m "adding new text files"`

###  To check the overview of recent commitments
 
`git log`

### Remote Repositories
We've gone ahead and created a new empty GitHub repository for you to use with Try Git at https://github.com/ashwini06/Github_tutorial  To push our local repo to the GitHub server we'll need to add a remote repository.

` git remote add origin git@github.com:ashwini06/Github_tutorial.git`

###  Pushing Remotely
The push command tells Git where to put our commits when we're ready, and boy we're ready. So let's push our local changes to our origin repo (on GitHub).

`git push -u origin master`

###  Pulling Remotely
Let's pretend some time has passed. We've invited other people to our GitHub project who have pulled your changes, made their own commits, and pushed them.

`git pull origin master`

### Differences
Uh oh, looks like there have been some additions and changes to the octocat family. Let's take a look at what is different from our last commit by using the git diff command.

`git diff`

### Branching Out
When developers are working on a feature or bug they'll often create a copy (aka. branch) of their code they can make separate commits to. Then when they're done they can merge this branch back into their main master branch.

`git branch clean_up`
`git branch`
`git checkout clean_up`

### Remove all the files

`git rm '*txt'`

### Commiting Branch Changes
Now that you've removed all the cats you'll need to commit your changes
`git commit -m "removed all text files"`

### Adding new branches changes to git_repo

`git push origin clean_up`

### Preparing to Merge
Alrighty, the moment has come when you have to merge your changes from the clean_up branch into the master branch.

`git merge clean_up`









