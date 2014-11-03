[Week 1 Home](../)

# U1.W1: Git Remote and Merge

## Learning Competencies

- Explain what a remote is
- Set up remotes for origin and upstream in your forked repostory

## Summary

Git uses remote URLs to figure out where to go on the Internet to push and pull files. By setting a remote, you are basically telling git exactly where to go when you want to save (push) your work, get (pull) your work to your computer, or fetch changes from the repo you forked from.

## Releases:

## Release 0: Watch
Watch this video about setting up remotes.

[![Remotes, fetching, and merging](http://img.youtube.com/vi/5IIPWznBvok/0.jpg)](http://www.youtube.com/watch?v=5IIPWznBvok)

<!-- [Remotes, fetching and merging](https://www.youtube.com/watch?v=5IIPWznBvok) -->

What do your remotes look like? use `git remote -v` to check the URLs of your remotes.

## Release 1: Add an Upstream

Add the Devbootcamp repo as your upstream. It should look like this when you are finished (as long as you are using HTTPS -- if you are using SSH, the urls will look a bit different).

```shell
origin  https://github.com/[USERNAME]/phase-0-unit-1.git (fetch)
origin  https://github.com/[USERNAME]/phase-0-unit-1.git (push)
upstream  https://github.com/Devbootcamp/phase-0-unit-1.git (fetch)
upstream  https://github.com/Devbootcamp/phase-0-unit-1.git (push)
```

[USERNAME] should be your own user name.

## Release 2: Fetching Changes

When your new week is released, or when we make important updates to the curriculum mid-week, you'll want to return to this challenge and follow the video instructions on fetching and merging from Devbootcamp's repo.

If we specify you need to fetch from a specific branch, make sure to note that with your fetch and merge commands. This will only happen after you finish a unit and we prepare your previous unit materials for the new students.

```shell
$ git fetch upstream <BRANCH>
# this will grab the upstream remote's branches

git merge upstream/<BRANCH>
# This will merge the upstream branch into your local, forked repository
```

It's important to know that fetching changes will not impact your work at all. Git will ensure everything is kept, and if two files are different, it will keep both versions and ask you to manually decide which section you want to keep. This is called a merge conflict. If you run into a merge conflict in Phase 0, you'll want to run through the video below for instructions on how to fix it.

[![Merge Conflict](http://img.youtube.com/vi/NW9AVnzx1B8/0.jpg)](http://www.youtube.com/watch?v=NW9AVnzx1B8)

<!-- [Merge Conflict](https://www.youtube.com/watch?v=NW9AVnzx1B8)
 -->
## Reflect
In the [my_reflection.md](my_reflection.md) file, answer the questions. Then go through the process of adding your changes, committing, and pushing. You should see your answers live on github!
