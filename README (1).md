# Task 6: Host a Static Website with GitHub Pages

## Objective
Deploy a simple static HTML website using GitHub Pages.

## Tools Used
- HTML
- CSS
- Git and GitHub
- GitHub Pages

## Project Files
- `index.html` — the website's main page, styled with CSS.
- `README.md` — project overview and deployment instructions.

## Steps to Deploy
1. Create a new repository on GitHub named `task-6-github-pages`.
2. Upload `index.html` and `README.md` to the repository's root folder.
3. Open the repository's **Settings**.
4. Select **Pages** from the sidebar.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/(root)` folder, then click **Save**.
7. Wait for GitHub Pages to finish deploying.
8. Open the live website using the URL shown in the Pages settings.

## Website URL
The published URL will look like this:

`https://YOUR-USERNAME.github.io/task-6-github-pages/`

Replace `YOUR-USERNAME` with your GitHub username.

## How to Update the Website
Edit `index.html`, commit the changes, and push them to the configured branch. GitHub Pages will publish the updated website.

## Interview Questions

### 1. What is GitHub Pages?
GitHub Pages is a hosting service that publishes static websites directly from a GitHub repository.

### 2. Can you host dynamic apps here?
GitHub Pages supports static files such as HTML, CSS, and JavaScript. It does not run server-side applications or backend code.

### 3. What are the limits of GitHub Pages?
It is intended for static websites and has limits on site size, bandwidth, and build usage. It does not support server-side execution.

### 4. How do you update the website?
Edit the website files, commit the changes, and push them to the branch configured in GitHub Pages.

### 5. What happens when you delete the repository?
The GitHub Pages website associated with that repository will no longer be available from that repository.

### 6. What is the default file that loads?
`index.html` is the standard default entry page for a static website.

### 7. Can you use a custom domain?
Yes. Add the domain in **Settings → Pages**, configure the required DNS records with your domain provider, and enable HTTPS when available.

## Submission Checklist
- [ ] Created a GitHub repository
- [ ] Uploaded `index.html` and `README.md`
- [ ] Enabled GitHub Pages for `main` and `/(root)`
- [ ] Tested the live website
- [ ] Copied the repository URL and live website URL for submission
