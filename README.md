Hello! We're a team building a project that helps young people learn creative digital skills. We want to know what skills and topics you are most interested in. Your feedback is crucial to help us design a free program based on your motivations. This anonymous survey takes just a few minutes. Thank you for helping us!

**Hosting (GitHub Pages)**

- **What I added:** a GitHub Actions workflow at `.github/workflows/deploy-pages.yml` and a `.nojekyll` file so the repository root is published as a static site.
- **How to publish:** commit and push the repository to GitHub (push to the `main` branch). The workflow runs on push and will publish the site to GitHub Pages.
- **Expected URL:** Once the workflow completes, the survey will be available at `https://IRAC88.github.io/creative-skills-survey/` (replace `IRAC88`/`creative-skills-survey` if your GitHub account or repo differs).
- **Push commands:**

```bash
git add .
git commit -m "Add Pages deploy workflow and hosting instructions"
git push origin main
```

- **Verify:** go to the Actions tab on GitHub, wait for the `Deploy to GitHub Pages` workflow to finish, then open the expected URL. If Pages isn't enabled automatically, visit the repository Settings → Pages and ensure the deployment target is set to `GitHub Actions`.

If you want, I can also open a PR or push these changes for you (I need your permission to push). 
Yes, please push the changes and help me to run the survey, respectively the URL link. I'm a newcomer at GitHub;)
