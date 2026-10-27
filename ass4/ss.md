# Assignment 4 – Repository with at Least Three Meaningful Commits

## Objective
To create a Git repository and maintain a history of at least three meaningful commits.

## Step 1: Configure Git Identity

```bash
git config --global user.name "Jyoti Bharti"
git config --global user.email "your-email@example.com"
```

Replace the example email with your Git-configured email address.

## Step 2: Initialize the Repository

```bash
git init
git branch -M main
```

## Step 3: Create Three Meaningful Commits

### Commit 1: Add README

```bash
git add README.md
git commit -m "docs: add project README"
```

### Commit 2: Add Setup and Git Assignments

```bash
git add 01-*.md 02-*.md 03-*.md 04-*.md 05-*.md
git commit -m "docs: add setup and Git assignments"
```

### Commit 3: Add HTML Basics Assignments

```bash
git add 06-*.html 07-*.html 08-*.html 09-*.html 10-*.html
git commit -m "feat: add HTML basics assignments"
```

Note: Run these commands when the corresponding files exist in your repository. If you are using an existing repository, do not initialize a new repository unnecessarily.

## Step 4: Verify Commit History

```bash
git log --oneline
```

This command displays the commit history and helps verify that at least three commits have been created.

## Good Commit Message Rules

- Use clear and meaningful messages.
- Use prefixes such as `docs:`, `feat:`, `fix:`, and `style:`.
- Keep each commit focused on one logical change.

## Conclusion

Git commits help track project changes and maintain a clear development history. A repository with at least three meaningful commits demonstrates basic version-control skills.