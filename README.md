# Privacy Policy - GitHub Pages Setup

This folder contains the privacy policy for Classmo (MonLivreCegep).

## Setup Instructions

### 1. Create a new GitHub repository

```bash
# Navigate to this folder
cd /Users/nicolasarsenault/Desktop/MonLivreCegep/privacy-policy

# Initialize git repo
git init

# Add files
git add .

# Commit
git commit -m "Add privacy policy"
```

### 2. Create repository on GitHub

1. Go to https://github.com/new
2. Name it: `monlivrecegep-privacy`
3. Keep it **Public** (required for free GitHub Pages)
4. Don't initialize with README (you already have files)
5. Click "Create repository"

### 3. Push to GitHub

```bash
git remote add origin https://github.com/Nicolas-Arsenault/monlivrecegep-privacy.git
git branch -M main
git push -u origin main
```

### 4. Enable GitHub Pages

1. Go to your repo: https://github.com/Nicolas-Arsenault/monlivrecegep-privacy
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under "Source", select **Deploy from a branch**
5. Select branch: **main**
6. Select folder: **/ (root)**
7. Click **Save**

### 5. Wait for deployment

- GitHub will build and deploy your site
- This takes 1-2 minutes
- You'll see a green checkmark when done

### 6. Your privacy policy URL

Once deployed, your privacy policy will be available at:

```
https://nicolas-arsenault.github.io/monlivrecegep-privacy/
```

## Updating the Privacy Policy

To update the policy:

1. Edit `index.html`
2. Commit and push:
   ```bash
   git add .
   git commit -m "Update privacy policy"
   git push
   ```
3. GitHub Pages will automatically redeploy

## App Store Submission

When submitting to the App Store, use this URL for the privacy policy field:

```
https://nicolas-arsenault.github.io/monlivrecegep-privacy/
```
