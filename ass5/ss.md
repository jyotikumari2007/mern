# Assignment 5 – GitHub Repository Link

## Objective
To upload the local project to GitHub and submit the repository link.

## Step 1: Create a GitHub Repository

1. Open [GitHub](https://github.com/).
2. Click **New repository**.
3. Enter the repository name: `html-css-assignments`.
4. Select Public if your assignment needs to be publicly accessible.
5. Leave the README, `.gitignore`, and license options unchecked if your local project already contains these files.
6. Click **Create repository**.

## Step 2: Connect the Local Repository to GitHub

Open the terminal in your local project folder and run:

```bash
git remote add origin https://github.com/YOUR-USERNAME/html-css-assignments.git
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username.

If an `origin` remote already exists, check it using:

```bash
git remote -v
```

If it points to the wrong repository, update it instead of adding it again:

```bash
git remote set-url origin https://github.com/YOUR-USERNAME/html-css-assignments.git
```

## Step 3: Verify the Repository

1. Open the repository page on GitHub.
2. Refresh the page.
3. Confirm that the project files and commit history are visible.

## Optional: Host the Project Using GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under Build and deployment, choose the `main` branch and `/ (root)` folder.
4. Click **Save**.

If GitHub Pages supports your project setup, the website will be available at:

`https://YOUR-USERNAME.github.io/html-css-assignments/`

## Submission

**Repository Link:** `https://github.com/YOUR-USERNAME/html-css-assignments`

Replace the placeholder with your actual GitHub username and submit the working repository URL.

## Conclusion

The project has been uploaded to GitHub, where its files and commit history can be viewed. GitHub Pages can optionally be used to publish the website online.