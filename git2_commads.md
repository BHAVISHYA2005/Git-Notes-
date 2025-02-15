Adding Files
bash
Copy
Edit
git add <File_Path>
Stages a specific file.

bash
Copy
Edit
git add .
Stages all changes in the current directory.

Viewing Changes
bash
Copy
Edit
git diff
Shows changes between the working directory and the staging area.

Committing Changes
bash
Copy
Edit
git commit -m 'Commit message'
Commits staged changes with a message.

Checking Status
bash
Copy
Edit
git status
Displays the state of the working directory and staging area.

Viewing Commit History
bash
Copy
Edit
git log
Shows commit logs.

bash
Copy
Edit
git log --oneline
Displays commit logs in a compact form.

Showing Commit Details
bash
Copy
Edit
git show <commit_id>
Displays detailed information about a specific commit.

Blaming Changes
bash
Copy
Edit
git blame <file_name>
Shows who last modified each line of a file.

Tip: Avoid pushing all changes in a single commit. Stage and commit related changes separately to maintain clarity and a clean project history.

Reverting Changes
bash
Copy
Edit
git reset --hard <commit_id>
Resets the current branch to a specified commit, discarding all changes after that commit.

bash
Copy
Edit
git revert <commit_id>
Creates a new commit that undoes the changes from a specified commit.

Pushing Changes
bash
Copy
Edit
git remote add origin <Remote_server_name>
Adds a new remote repository.

bash
Copy
Edit
git remote -v
Verifies the remote repository URL.

bash
Copy
Edit
git push -u origin main
Pushes commits to the 'main' branch on the remote repository and sets the upstream.

bash
Copy
Edit
git push -f
Forces the push, overwriting the remote content.

Branching
bash
Copy
Edit
git branch <branch_name>
Creates a new branch.

bash
Copy
Edit
git checkout <branch_name>
Switches to the specified branch.

bash
Copy
Edit
git checkout -b <branch_name>
Creates and switches to a new branch.

bash
Copy
Edit
git merge <branch_name>
Merges the specified branch into the current branch.

bash
Copy
Edit
git branch -d <branch_name>
Deletes the specified branch.
