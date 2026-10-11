# Zoya Fatima Portfolio

A static HTML portfolio. No build step or package installation is required.

## Publish with GitHub Pages

1. Create an empty GitHub repository for this portfolio, for example `zoya-fatima-portfolio`. A public repository is the simplest option for a public portfolio; a private repository may require a GitHub plan that supports Pages. Do not add a README or other starter files on GitHub.
2. In this folder, run the following commands, replacing `<USERNAME>` and the repository name as needed:

	```powershell
	git init -b main
	git add index.html case-studies.html work-rewritten-v5.html favicon.png zoya-resume-2026.pdf README.md
	git commit -m "Add portfolio site"
	git remote add origin https://github.com/<USERNAME>/zoya-fatima-portfolio.git
	git push -u origin main
	```

3. In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. Wait for the Pages deployment to finish. GitHub will show the published URL in the Pages settings.

The site links to the HTML files by their filenames, uses `favicon.png` for its browser icon, and offers `zoya-resume-2026.pdf` as a download. Keep these filenames and the root-level layout unchanged unless you update the links too.
