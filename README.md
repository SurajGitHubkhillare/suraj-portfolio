# Suraj Khillare — Personal Portfolio

A responsive, dark-modern portfolio built with plain HTML, CSS, and JavaScript. No build tools or framework are required.

## Included
- Responsive navigation and mobile menu
- Dark modern design with accent colors and animated details
- About, skills, projects, education, and contact sections
- Project category filters
- Resume, GitHub, LinkedIn, and email links
- Scroll reveal effects and reduced-motion support

## Before publishing
1. Replace `assets/profile-photo.svg` with your own portrait photo. For the simplest replacement, save your image as `profile-photo.jpg`, then update the image path in `index.html` to `assets/profile-photo.jpg`.
2. Review the education details and project descriptions to ensure they are accurate and up to date.
3. Replace each project card's GitHub profile link with its specific repository or live demo URL when available.
4. Open `index.html` in your browser to preview the site.

## Publish on GitHub Pages
1. Sign in to GitHub and create a new **public** repository named `suraj-portfolio` (or another name you prefer).
2. Upload all files and folders in this package. Make sure `index.html` is at the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait a few minutes. GitHub will show the published website URL in the Pages settings.

For a project repository named `suraj-portfolio`, the URL is typically:
`https://surajgithubkhillare.github.io/suraj-portfolio/`

The URL depends on your GitHub account name and repository name. If you instead create a repository named `SurajGitHubkhillare.github.io` (matching your account name exactly as GitHub expects), it can be published as a user site at `https://surajgithubkhillare.github.io/`.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Publish using Git from VS Code (optional)
Open a terminal in this folder and run:

```bash
git init
git add .
git commit -m "Build personal portfolio"
git branch -M main
git remote add origin https://github.com/SurajGitHubkhillare/suraj-portfolio.git
git push -u origin main
```

Create the repository on GitHub before running the commands. If you choose a different repository name, update the remote URL accordingly.

## Notes
- This is a static website. GitHub Pages can host it without a server.
- The contact button uses `mailto:` and opens the visitor's email app. A real form that stores or sends messages needs a form service or backend.
- Do not put passwords, API keys, private documents, or other secrets in a public repository.
