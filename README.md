This is to test and understand the working of git and the git commands by self teaching

Git Commands – Complete Reference with Explanations and Examples
1. Git Configuration
Command:
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

Use Case:
Set your identity globally for all Git repositories on your machine.

2. Initialize a Git Repository
Command:
git init

Use Case:
Start a new local Git repository in your current folder.

3. Clone a Repository
Command:
git clone https://github.com/username/repo-name.git

Use Case:
Download a repository from a remote server (like GitHub) to your local machine.

4. Check Status
Command:
git status

Use Case:
View modified, added, deleted, or untracked files in your working directory.

5. Add Files to Staging
Command:
git add filename.ext
git add .

Use Case:
Stage specific files or all changes for the next commit.

6. Commit Changes
Command:
git commit -m "Descriptive message"

Use Case:
Save staged changes to the local repository with a commit message.

7. Add and Commit in One Step (Tracked Files Only)
Command:
git commit -am "Message"

Use Case:
Quickly add and commit modified files that are already being tracked.

8. Push Changes to Remote
Command:
git push origin main

Use Case:
Upload your local commits to the remote repository's main branch.

9. Pull Changes from Remote
Command:
git pull origin main

Use Case:
Fetch and merge the latest changes from the remote repository into your current branch.

10. Fetch Without Merge
Command:
git fetch

Use Case:
Download changes from remote without merging. Useful for reviewing changes before applying.

11. Merge Changes
Command:
git merge origin/main

Use Case:
Manually apply fetched changes to your current branch.

12. Pull with Rebase
Command:
git pull --rebase

Use Case:
Apply your local changes on top of the latest changes from the remote, creating a cleaner history.

13. View Commit History
Command:
git log

Use Case:
Show the detailed history of commits.

14. View Commit History in One Line
Command:
git log --oneline

Use Case:
Compact summary of commit history.

15. Show Changes in Last Commit
Command:
git show

Use Case:
Display the details (diff, metadata) of the most recent commit.

16. Compare Working Directory with Last Commit
Command:
git diff

Use Case:
See changes made since the last commit.

17. Create a Branch
Command:
git branch new-branch

Use Case:
Create a new branch from the current one.

18. Switch Branches
Command:
git checkout branch-name

Use Case:
Switch to another branch.

19. Create and Switch in One Step
Command:
git checkout -b new-branch

Use Case:
Create and immediately switch to a new branch.

20. Delete a Branch
Command:
git branch -d branch-name

Use Case:
Delete a local branch that is no longer needed.

21. Stash Changes Temporarily
Command:
git stash

Use Case:
Save uncommitted changes without committing them, to switch branches or pull.

22. Apply Last Stashed Changes
Command:
git stash apply

Use Case:
Restore the most recently stashed changes.

23. View Stash List
Command:
git stash list

Use Case:
View all saved stashes.

24. Remove All Stashes
Command:
git stash clear

Use Case:
Clear the stash history.

25. Undo Last Commit (Keep Changes)
Command:
git reset --soft HEAD~1

Use Case:
Undo the last commit but keep the changes staged.

26. Undo Last Commit (Discard Changes)
Command:
git reset --hard HEAD~1

Use Case:
Completely remove the last commit and its changes.

27. Discard Local Changes (Unstaged)
Command:
git checkout -- filename.ext

Use Case:
Revert a specific file to the last committed state.

28. Remove All Local Changes (Dangerous)
Command:
git reset --hard

Use Case:
Remove all local modifications and return to the last commit.

29. View All Branches
Command:
git branch

Use Case:
List all local branches.

30. View Remote Branches
Command:
git branch -r

Use Case:
List all remote branches.

31. View All Remote and Local Branches
Command:
git branch -a

Use Case:
List both local and remote branches.

32. View All Recent Actions (Reflog)
Command:
git reflog

Use Case:
Track all changes to HEAD (useful for undoing mistakes).