#when you get this error use this command:- (git pull origin main) and then push again (git push -u origin main).
<img width="1195" height="277" alt="image" src="https://github.com/user-attachments/assets/b7a46985-9fe2-456c-884c-4f9473b74ad7" />


# Set your global Git email (used for commits)
git config --global user.email "email"

# Set your global Git username
git config --global user.name "username"

# Initialize a new Git repository in the current directory
git init

# Stage a specific file for commit
git add <filename>

# Stage all changes (new, modified, deleted files) for commit
git add .

# Commit staged changes with a message
git commit -m "message"

# Show the current status of the working directory and staging area
git status

# Display commit history in a compact, one-line format
git log --oneline

# Used to specify files/folders to ignore via .gitignore (not a command itself)
# git ignore → Create/edit a `.gitignore` file manually

# Used to keep empty folders in Git by adding a placeholder file
# git keep → Create a `.keep` file manually inside the folder

# Show changes between working directory and staging area
git diff

# Show changes between staged files and the last commit
git diff --staged

# List all stashed changes
git stash list

# List all tags in the repository
git tag

# Switch to another branch
git switch "branchname"

# List all branches in the repository
git branch

# Checkout a branch (older syntax, still widely used)
git checkout "branchname"

# Resolve merge conflicts by committing the merge manually
git commit -m "Merge remote-tracking branch 'origin/main'"

# Merge another branch into the current branch
git merge

# Show the URLs of remote repositories
git remote -v

# Add a remote repository (usually GitHub origin)
git remote add origin "link"

# Push local commits to the remote repository and set upstream
git push -u origin main
