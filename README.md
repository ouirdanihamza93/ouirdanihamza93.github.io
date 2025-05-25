# GitHub Pages Setup Instructions

This document provides step-by-step instructions for setting up your academic portfolio using GitHub Pages.

## Step 1: Create a GitHub Account

If you don't already have a GitHub account:
1. Go to [GitHub.com](https://github.com)
2. Click "Sign up" and follow the registration process

## Step 2: Create a New Repository

1. After logging in, click the "+" icon in the top right corner and select "New repository"
2. Name your repository: `yourusername.github.io` (replace "yourusername" with your actual GitHub username)
3. Make sure the repository is set to "Public"
4. Click "Create repository"

## Step 3: Upload Your Files

### Option 1: Upload via GitHub Web Interface
1. In your new repository, click the "Add file" button and select "Upload files"
2. Upload the following files from this package:
   - `index.html`
   - `styles.css`
   - Your profile photo (rename it to `profile-image.jpg`)
   - Your thesis PDF
   - Your presentation PDF
   - Any other academic documents you want to share
3. Click "Commit changes"

### Option 2: Upload via Git (for advanced users)
1. Clone the repository to your computer
2. Copy all files to the cloned repository folder
3. Use git commands to add, commit, and push the files

## Step 4: Customize Your Page

1. Edit the `index.html` file to:
   - Update your personal information (name, contact details, etc.)
   - Replace placeholder text in the "About Me" section
   - Update document links to point to your actual PDF files
   
   For example, change:
   ```html
   <a href="#" class="document-link">View Presentation</a>
   ```
   to:
   ```html
   <a href="presentation.pdf" class="document-link">View Presentation</a>
   ```

2. Replace `profile-image.jpg` with your actual photo (make sure to name your photo file `profile-image.jpg` or update the filename in the HTML)

## Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings"
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait a few minutes for your site to be published

## Step 6: Access Your Website

Your academic portfolio will be available at: `https://yourusername.github.io`

## Updating Your Site

Whenever you want to update your site:
1. Go to your repository on GitHub
2. Navigate to the file you want to edit
3. Click the pencil icon to edit
4. Make your changes
5. Click "Commit changes"

Your site will automatically update with the new changes.

## Additional Tips

- Keep your PDFs and other documents updated
- Consider adding Google Analytics to track visitors
- You can purchase a custom domain and connect it to your GitHub Pages site for a more professional URL
