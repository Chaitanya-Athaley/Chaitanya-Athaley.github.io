# Java Full Stack Developer Portfolio

A clean, fast, recruiter-friendly static portfolio website for a Java Full Stack Software Developer. It is built with plain HTML, CSS, and JavaScript so it can be hosted for free on GitHub Pages without a backend or build step.

## Folder Structure

```text
.
|-- index.html
|-- style.css
|-- script.js
|-- assets/
|   `-- profile.png
|-- resume.pdf
`-- README.md
```

Optional files you can add later:

```text
.
`-- og-image.png
```

## How to Edit in VS Code

1. Open this folder in VS Code.
2. Edit `index.html` to update your name, title, profile summary, projects, experience highlights, contact links, and resume link.
3. Edit `style.css` to change colors, spacing, typography, or layout.
4. Edit `script.js` only if you want to change the mobile menu or dark mode behavior.
5. Replace `assets/profile.png` with your preferred profile photo if you want a different image.
6. Open `index.html` in your browser to preview locally.

## Replace These Placeholders

Search for these values in `index.html` and replace them:

- `resume.pdf`
- `assets/profile.png`
- Project repository URLs and project descriptions
- Company names, domains, responsibilities, and real project outcomes

If you add a resume, place a file named `resume.pdf` in the same folder as `index.html`. If your resume file has another name, update both resume links in `index.html`.

To change the profile photo, replace `assets/profile.png` with another square or portrait image using the same filename. A 512 x 512 image works well.

## Content Tips

- Keep the hero section short and role-specific.
- Replace project examples with real full stack or backend projects when possible.
- Use honest impact statements. Prefer specific outcomes only when you can support them.
- Make Java, Spring Boot, Angular, JavaScript, microservices, APIs, databases, Kafka, Redis, AWS, Docker, Kubernetes, performance, and reliability easy to find.
- Keep GitHub, LinkedIn, email, and resume links current.

## Push to GitHub

Run these commands from this folder after creating a repository on GitHub:

```bash
git init
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/Chaitanya-Athaley/your-repository-name.git
git push -u origin main
```

If this folder is already inside an existing Git repository, use:

```bash
git add index.html style.css script.js README.md
git commit -m "Add portfolio website"
git push
```

## Enable GitHub Pages

1. Open your repository on GitHub.
2. Go to **Settings**.
3. Select **Pages** from the left sidebar.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch.
6. Select the `/root` folder.
7. Click **Save**.
8. Wait for GitHub to publish the site.

Your site will usually be available at:

```text
https://Chaitanya-Athaley.github.io/your-repository-name/
```

## Recommended Repository Naming

For a personal GitHub Pages site at the root URL, name the repository:

```text
Chaitanya-Athaley.github.io
```

That publishes to:

```text
https://Chaitanya-Athaley.github.io/
```

For a project repository, any repository name works, and the site publishes under:

```text
https://Chaitanya-Athaley.github.io/repository-name/
```

## GitHub Pages Notes

- All paths are relative, so the site works locally and on GitHub Pages.
- No backend, package manager, framework, or build process is required.
- Keep `index.html` in the repository root for the simplest GitHub Pages setup.
