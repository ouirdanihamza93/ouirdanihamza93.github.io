# Minimalist GitHub Pages Setup Instructions

This document provides step-by-step instructions for setting up your minimalist academic portfolio using GitHub Pages.

## Step 1: Repository Setup

If you already have a repository (like your current `ouirdanihamza93/ouirdanihamza`):
1. Navigate to your existing repository
2. Replace the existing files with these new minimalist template files

If you want to create a new repository:
1. Create a repository named `yourusername.github.io` (for a cleaner URL)
2. Upload these template files to the new repository

## Step 2: Upload Your Files

1. In your repository, click the "Add file" button and select "Upload files"
2. Upload the following files from this package:
   - `index.html`
   - `styles.css`
   - Your profile photo (rename it to `profile-image.jpg`)
   - Your thesis PDF
   - Your presentation PDF
3. Click "Commit changes"

## Step 3: Customize Your Page

1. Edit the `index.html` file to:
   - Update any personal information if needed
   - Replace placeholder text in the "Bio" section
   - Update document links to point to your actual PDF files
   
   For example, change:
   ```html
   <a href="#">View Presentation</a>
   ```
   to:
   ```html
   <a href="presentation.pdf">View Presentation</a>
   ```

2. Replace `profile-image.jpg` with your actual photo (make sure to name your photo file `profile-image.jpg` or update the filename in the HTML)

3. Update the links section with your actual social media or professional profiles:
   ```html
   <div class="links">
       <a href="https://github.com/yourusername">GitHub</a>
       <a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
       <a href="your-cv.pdf">Download CV</a>
   </div>
   ```

## Step 4: Enable GitHub Pages

If not already enabled:
1. Go to your repository on GitHub
2. Click "Settings"
3. Select "Pages" from the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"

## Step 5: Access Your Website

Your academic portfolio will be available at:
- If using `yourusername.github.io` repository: `https://yourusername.github.io`
- If using a custom repository name: `https://yourusername.github.io/repositoryname/`

## Updating Your Site

Whenever you want to update your site:
1. Go to your repository on GitHub
2. Navigate to the file you want to edit
3. Click the pencil icon to edit
4. Make your changes
5. Click "Commit changes"

Your site will automatically update with the new changes.
