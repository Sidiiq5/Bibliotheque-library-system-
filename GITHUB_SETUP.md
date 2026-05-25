# GitHub Push Guide for Bibliotheque

## Step 1: Create a Repository on GitHub

1. Go to [GitHub](https://github.com) and sign in to your account
2. Click the **+** icon in the top-right corner and select **New repository**
3. Name your repository: `bibliotheque` (or your preferred name)
4. Add a description: "A comprehensive web-based library management system with borrow/return functionality and extended catalog"
5. Choose **Public** or **Private** based on your preference
6. ✅ Check "Add a README file" (optional, since we have one)
7. Click **Create repository**

## Step 2: Initialize Git Locally & Push

Open a terminal/command prompt and run these commands:

```bash
# Navigate to your project folder
cd path/to/your/bibliotheque/folder

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial commit: Merged library system and books catalog"

# Add remote repository (replace USERNAME/REPO with your GitHub details)
git remote add origin https://github.com/USERNAME/bibliotheque.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Verify on GitHub

1. Go to your GitHub repository
2. You should see all three files:
   - `bibliotheque-merged.html` (main application)
   - `README.md` (documentation)
   - `.gitignore` (git ignore rules)

## Future Updates

To push new changes:

```bash
git add .
git commit -m "Your commit message"
git push origin main
```

## Files to Push

- ✅ `bibliotheque-merged.html` - Main application (recommended)
- ✅ `library-system.html` - Original system
- ✅ `bibliotheca.html` - Original catalog
- ✅ `README.md` - Documentation
- ✅ `.gitignore` - Git ignore file

## Troubleshooting

### Authentication Error?
If you get authentication errors, use a Personal Access Token:
1. Go to GitHub → Settings → Developer settings → Personal access tokens
2. Generate a new token with `repo` scope
3. Use the token as your password when prompted

### Already have git remote?
If you already pushed and need to change the remote:
```bash
git remote remove origin
git remote add origin https://github.com/USERNAME/bibliotheque.git
```

## Optional Enhancements for GitHub

### Add a License
Create a `LICENSE` file in your repository root:
```
MIT License (recommended for open source)
Apache 2.0
GNU GPL v3
```

### Add GitHub Pages
Make your library system accessible online:
1. Go to repository **Settings** → **Pages**
2. Select **main** branch as source
3. Save
4. Your site will be available at `https://username.github.io/bibliotheque`

### Add Tags for Releases
```bash
git tag -a v1.0 -m "Initial release"
git push origin v1.0
```

## Need Help?

- [GitHub Documentation](https://docs.github.com)
- [Git Tutorial](https://git-scm.com/book)
- GitHub's built-in help: [Github Help](https://help.github.com)
