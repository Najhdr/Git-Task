## What is Git?

```
 Git is distributed version control software system that 
 is capable of managing version of source code or data. 
 Often used to control source code by programmers 
 who are devloping software collaboratively.

 Git tracks changes by taking snapshots of your project 
 files at different points in time, allowing you to revisit
  or compare versions whenever needed. Developers make 
  changes locally, then commit those changes as discrete
   units with descriptive messages. These commits form a 
   timeline of the project’s development.
 ```

## Different stages of Git:

``` Working Directory is a current state of the project files. 
Its a staging Area; place where you can group 
changes before committing them. 

Staging acts as a prep zone for changes before they are 
committed to the main repository. This guide provides 
an in-depth look at how to interact with the staging area, 
including adding, modifying, and removing changes.

 Commit includes a comment that records information about the changes, 
 and usually becomes the new tip of the branch. Git 
 doesn't automatically include any files you move, 
 change, or delete in a commit. This prevents you 
 from accidentally including a change or file, like a temporary directory.
 
  ```

  ## what is a Branch in Git?

 ```
  Branches in Git provide isolated environments within a 
  repository to develop features, fix bugs, 
  or experiment without affecting the main codebase. 
  
  Changes are saved as commits, which act like 
  snapshots of the project at a specific point in time. 
  
  When work on a branch is complete, Git allows 
  these changes to be merged back into the main branch, 
  combining updates from multiple contributors in a controlled way.
  
  This structure supports parallel development 
  and helps prevent conflicts when multiple 
  people are working on the same project.
  ```
   ## what to use Git?
   ``` Some of the most important and most used commands that you'll find there are:
   ```
   ```
   - git clone [url] Clone (download) a repository that already 
   exists on GitHub, including all of the files, branches, and commits.
   - git status always a good idea, this command shows you what b
   ranch you're on, what files are in the working or staging directory, 
   and any other important information.
   - git branch: This shows the existing branches in your local repository. 
   - git branch [branch-name] to create a branch from your current location
   - git checkout [branch-name]: Switches to the specified 
   branch and updates the working directory.
   -git add [file]: Snapshots the file in preparation
    for versioning, adding it to the staging area.
    -git commit -m "descriptive message": Records 
    file snapshots permanently in the version history.
    -git pull: Updates your current local working branch 
    with all new commits from the corresponding remote branch on GitHub. 
    -git push: Uploads all local branch commits to the remote.
    -







