# Personal Resume Website

A three-page personal resume website created with HTML and CSS.

## Files
- `index.html` — Home / resume
- `hobbies.html` — Hobbies and interests
- `contact.html` — Contact information
- `style.css` — Shared responsive styling
- `SUBMISSION.md` — Assignment submission details and references

## Before publishing
1. Update the example email and social profile details in `contact.html`.
2. Check the personal details, education, project and activity descriptions.
3. Open `index.html` in a browser to preview the website.

## Publish with GitHub Pages
Create a repository named `my-resume-site`. Open a terminal in this folder and run:

```bash
git init
git add .
git commit -m "Initial resume site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/my-resume-site.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username. Then go to **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save.

Website URL: `https://YOUR-USERNAME.github.io/my-resume-site/`

## Mistake in the handout
The `git remote add origin` command has an incorrectly formatted Markdown-style URL. Git expects one plain repository URL without Markdown brackets, parentheses or an escaped angle bracket around the username placeholder.
