# GPS 1.1 Git work flow and branching

## Learning Competencies
- Establish a git workflow
- Explain what a git branch is and its purpose
- Demonstrate the ability to research for debugging or to better understand concepts


## Summary

Welcome to the wonderful world of git workflow. We are going to work through a simple git challenge, including making branches, merging, pull requests and merge conflicts.

Make sure that you use all the resources available to you, your pair, the git docs and your guide.

## Releases

## Release 0: Create your repo

Choose 1 member of your pair and create a new repo called phase-0-gps-1. Initialize this with a readme, you can add the MIT license if you want others to contribute [reference on licenses](http://choosealicense.com/) but don't worry about it for this small project.

Add you pair and your guide as collaborators on this project and make sure that they have read and write access.

Driver will clone this repo to their computer and add another file called awesome_page.md to the directory (touch is a great command if you want to create files through the terminal). Add, commit and push this to your master. Now we have a base project to work with.

## Release 1: Clone the Repo

Both you and your pair should clone the repo to your own computer. You should both have a readme.md and the awesome_page.md file to work with.

## Release 2: Create a Feature Branch

Now the driver will create a feature branch called awesome-feature. Change the readme.md to list the terminal commands that you have used so far. If you are feeling adventurous you can add a brief description of each command. After you've made the changes, push your branch to GitHub and do a pull request to master. The navigator should review the pull request on GitHub and merge after a brief review.

Take some time to talk about why you would bother creating a feature branch in the first place. Make sure you could explain what a branch is, how to create one, and how to navigate between them.

## Release 3: Fetch and Merge

Switch driver and navigator roles, now the other partner will make modifications. But first the new driver will need to incorporate the changes already pushed to GitHub. Fetch and merge the changes to your local repository. (git fetch <remote> <branch>)

What is the difference between fetch/merge and pull?

Make a new branch, we will make some changes to awesome_page.md. Show off some of your [markdown](http://daringfireball.net/projects/markdown/syntax) skills. Make something **bold**, *italic*, `some sort of code block` and a [link](http://daringfireball.net/projects/markdown/syntax). Add and commit your changes for awesome_page.md, push your branch to GitHub.

Make a pull request like last time. The navigator should review the diff of the request and merge it. You will be using this work flow all the time as a developer!

## Release 4: Merge Conflict
Sometimes you will encounter merge conflicts, but don't worry, once you've gone through a few, they aren't scary, so it's good to get practice now!

A merge conflict happens when two branches change the same file and try to merge them together. Here is how to create a small merge conflict:

1. Create a branch called small-conflict, make any change in awesome_page.md, add and commit.
2. Check out the master branch, in the same place that you made a change on awesome_page on the branch small-conflict, make a different change. Add and commit this change.
3. Merge the small-conflict branch to the master.
4. Resolve the merge conflicts.

You can imagine that in a big project, this can be a huge time waster. Good git work flow can prevent merge conflicts from being a problem.

Review [this](http://stackoverflow.com/questions/16490873/how-to-avoid-git-conflicts-in-a-team) discussion about preventing merge conflicts. It's good to keep in mind as you move forward with your git education.

## Release 5: Discuss

Confer with your partner and guide about what a good git work flow is, the purpose of git branching, feature branching, and pull requests. You are in the group of elite git users now!

## Release 6: Reflect
On your own, reflect on this challenge in the [my_reflection.md](my_reflection.md) file.
