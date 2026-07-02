# BMGIS Policy Pages

This folder contains the public policy pages for the BMGIS Android app.

These files are intended to be uploaded to a public GitHub repository and published using GitHub Pages.

Files included:

- `index.html` — BMGIS Privacy Policy
- `deletion.html` — BMGIS Account Deletion Information

Support contact used in these pages:

- `bmgis.my@gmail.com`

Suggested GitHub repository

- Repository name: `bmgis-policy`
- Repository description: `Public privacy policy and account deletion information for the BMGIS Android app.`
- Visibility: `Public`

How to publish with GitHub Pages

1. Sign in to GitHub.
2. Create a new public repository named `bmgis-policy`.
3. Upload these files into the root of the repository:
   - `index.html`
   - `deletion.html`
   - optionally `README.md`
4. Open the repository on GitHub.
5. Go to `Settings`.
6. Open `Pages` in the left menu.
7. Under `Build and deployment`, choose:
   - `Source` → `Deploy from a branch`
8. Under branch settings, choose:
   - Branch: `main`
   - Folder: `/ (root)`
9. Click `Save`.
10. Wait for GitHub Pages to publish the site.

Expected public URL

If your GitHub username is `hashnol`, the site URL should be:

- `https://hashnol.github.io/bmgis-policy/`

Your pages should then be available at:

- Privacy Policy:
  - `https://hashnol.github.io/bmgis-policy/`
- Account Deletion:
  - `https://hashnol.github.io/bmgis-policy/deletion.html`

How to use these links

Use the Privacy Policy URL in:

- Google Play Console privacy policy field
- the BMGIS app account/help section

Use the Account Deletion URL in:

- Google Play account deletion support information
- your privacy policy page

Before publishing to Google Play

Please verify:

- the email address is correct: `bmgis.my@gmail.com`
- the wording matches how BMGIS currently handles deletion requests
- the pages are publicly accessible without login

Current deletion wording

The current account deletion page says:

- users can request deletion from inside the app
- the request is recorded for follow-up processing
- the user is signed out after the request

If your deletion workflow changes later, update `deletion.html` accordingly.

Recommended next steps

1. Publish these pages on GitHub Pages.
2. Replace the placeholder privacy-policy link in the app with the real GitHub Pages URL.
3. Add the same privacy-policy URL in Google Play Console.
