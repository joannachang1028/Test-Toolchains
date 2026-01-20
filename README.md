# Test-Toolchains

## Viewing Repository History

There are several ways to view the history of this repository:

### Using Git Commands (Local)

If you have cloned this repository, you can view the history using these Git commands:

```bash
# View commit history with one commit per line
git log --oneline

# View detailed commit history
git log

# View commit history with graph visualization
git log --graph --oneline --all --decorate

# View commit history with file changes
git log --stat

# View commit history with full diff
git log -p
```

### Using GitHub Web Interface

You can view the repository history directly on GitHub:

1. Go to the repository page: https://github.com/joannachang1028/Test-Toolchains
2. Click on the **"Commits"** link (usually shown as "X commits" near the top of the file list)
3. Or click on the **"Insights"** tab and then select **"Network"** to see a visual representation of branches and commits

### Viewing History for Specific Files

To see the history of changes to a specific file:

```bash
# Using Git command line
git log -- <filename>

# Or on GitHub
# Navigate to the file and click "History" button
```