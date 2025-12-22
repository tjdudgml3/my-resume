# Personal Resume Website

This is a personal resume website built with HTML, CSS, and JavaScript.

## Project Structure
- `index.html`: The main HTML file containing the website structure and content.
- `style.css`: The CSS file for styling and responsive design.
- `script.js`: The JavaScript file for interactivity (mobile menu, smooth scrolling).
- `images/`: Directory containing project images.

## How to Deploy to GitHub Pages

Since the GitHub CLI (`gh`) is not installed, you can deploy this website using standard Git commands.

### Prerequisites
- You must have a GitHub account.
- You must have a repository created on GitHub (e.g., `my-resume`).

### Steps

1.  **Initialize Git (if not already done):**
    ```bash
    git init
    ```

2.  **Add all files:**
    ```bash
    git add .
    ```

3.  **Commit changes:**
    ```bash
    git commit -m "Initial commit: Resume website"
    ```

4.  **Rename the branch to main (optional but recommended):**
    ```bash
    git branch -M main
    ```

5.  **Add your GitHub repository as a remote:**
    Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name.
    ```bash
    git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
    ```

6.  **Push to GitHub:**
    ```bash
    git push -u origin main
    ```

7.  **Enable GitHub Pages:**
    - Go to your repository on GitHub.
    - Click on **Settings**.
    - Scroll down to the **Pages** section (or click "Pages" in the left sidebar).
    - Under **Source**, select `main` branch and `/ (root)` folder.
    - Click **Save**.

Your website will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`.
