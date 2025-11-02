# YSPM
This is my first git repository
<br>
Author- Shweta Patil 




git and github:
 Setup & Configuration
Command	Description
git config --global user.name "Your Name"	Set your Git username globally
git config --global user.email "you@example.com"	Set your Git email globally
git config --global core.editor code	Set VS Code as default Git editor
git config --list	View current configuration

📁 Initialize & Clone
Command	Description
git init	Initialize a new Git repository
git clone <repo-url>	Clone a remote repository

🔄 Basic Workflow
Command	Description
git status	Show status of changes
git add <file>	Stage a specific file
git add .	Stage all changes
git commit -m "message"	Commit changes with message
git push	Push commits to remote repo
git pull	Fetch and merge from remote
git fetch	Only fetch (without merge)

🌿 Branching
Command	Description
git branch	List all branches
git branch <name>	Create a new branch
git checkout <name>	Switch to a branch
git checkout -b <name>	Create and switch to branch
git merge <branch>	Merge a branch into current one
git branch -d <name>	Delete a branch
git switch <branch>	(Newer alternative to checkout)
git switch -c <new-branch>	Create and switch (alternative)

🔍 Logs & History
Command	Description
git log	Show commit history
git log --oneline	Compact commit history
git diff	Show unstaged changes
git diff --staged	Show staged changes
git show <commit>	Show specific commit content

⏪ Undo & Reset
Command	Description
git restore <file>	Undo changes to a file (unstaged)
git restore --staged <file>	Unstage a file
git reset	Unstage everything (keep changes)
git reset --hard	Reset everything (remove changes)
git revert <commit>	Create a new commit that reverts a past one

🔗 Remote Repositories
Command	Description
git remote -v	Show remote URLs
git remote add origin <url>	Add a remote repository
git push -u origin main	Push first time with upstream
git push origin <branch>	Push specific branch
git pull origin <branch>	Pull specific branch

📦 Stash
Command	Description
git stash	Save changes temporarily
git stash apply	Reapply stashed changes
git stash list	Show stashes
git stash drop	Remove a stash

🔄 Tags
Command	Description
git tag	List tags
git tag <name>	Create a new tag
git tag -d <name>	Delete a tag
git push origin <tag>	Push a tag to remote
git push origin --tags	Push all tags

🧪 Advanced / Useful
Command	Description
git cherry-pick <commit>	Apply a specific commit to current branch
git rebase <branch>	Reapply commits on top of another branch
git reflog	Show log of all refs (useful for recovery)
git clean -fd	Remove untracked files and dirs

🐙 GitHub CLI (optional but useful)
Command	Description
gh auth login	Login to GitHub via CLI
gh repo clone <repo>	Clone repo using GitHub CLI
gh pr create	Create pull request
gh issue list	List issues
gh repo create	Create a new GitHub repo
