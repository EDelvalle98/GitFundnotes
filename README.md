Git is a powerful version control system that tracks changes in files over time.
Basic Concepts
Repository: A directory that stores all the files and their history.
Commit: A snapshot of the repository's state at a particular point in time.
Branch: A parallel version of the repository, allowing you to work on different features independently.
Merge: Combining changes from one branch into another.
Pull Request: A request to merge changes from one branch into another.
Workflow
Initialize: Create a new Git repository.
Stage: Add files to the staging area for the next commit.
Commit: Create a snapshot of the staged files.
Push: Send your commits to a remote repository.
Pull: Get the latest changes from a remote repository.

Key Commands
git init: Creates a new Git repository.
git add <file>/ -A: Adds a file to the staging area. -A adds everything
git commit -m "<message>": Commits the staged changes with a message.
git push <remote> <branch>: Pushes commits to a remote repository.
git pull <remote> <branch>: Pulls changes from a remote repository.
Troubleshooting
git status: Shows the current state of your working directory.
git log: Displays a list of commits.
git reset --hard <commit>: Reverts to a specific commit.

Rebasing: Reorders commits on a branch.
Cherry-picking: Applies specific commits from one branch to another.
Stashing: Temporarily saves changes without committing them.
Branching Strategies: Different approaches to organizing branches (e.g., Gitflow, GitHub flow).
Collaborating with Others
Forking: Creating a copy of a repository to make changes.
Pull Requests: Submitting changes to the original repository for review.
