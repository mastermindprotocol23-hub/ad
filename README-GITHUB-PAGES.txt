GITHUB PAGES — ADMIN PANEL ALL-IN-ONE PACKAGE

FILES INCLUDED
- adminn.html: your existing admin panel (Firebase/backend code unchanged)
- index.html: opens adminn.html when the repository root URL is visited
- .github/workflows/deploy-pages.yml: deploys the repository to GitHub Pages using GitHub Actions

INSTALL INTO YOUR EXISTING REPOSITORY
1. Extract this ZIP.
2. Upload/copy the included adminn.html and index.html into the ROOT of repository "a" (beside each other).
3. Upload/copy .github/workflows/deploy-pages.yml to the same path in the repository. If a workflow file already exists with the same name, replace that workflow file with this one.
4. IMPORTANT: index.html redirects the root URL to adminn.html. If you currently have a public website homepage named index.html that you need to keep, make a backup before replacing it.
5. Commit and push the files to the main branch. If your default branch isn't main, edit the branch name in .github/workflows/deploy-pages.yml.
6. In GitHub, open Settings -> Pages -> Build and deployment -> Source, then select GitHub Actions.
7. Open the Actions tab and verify "Deploy admin panel to GitHub Pages" completes successfully.

URLS
- Root URL: https://mastermindprotocol23-hub.github.io/a/ (redirects to adminn.html)
- Direct admin panel: https://mastermindprotocol23-hub.github.io/a/adminn.html

BACKEND NOTE
The original adminn.html file is included unchanged. This package does not modify Firebase configuration, Firestore logic, or any backend code. GitHub Pages only serves static files; any backend endpoints must remain hosted separately.
