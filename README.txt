TEMERICK.DEV — GITHUB PAGES PACKAGE

Required website files:
- index.html
- portrait.jpeg
- CNAME
- .nojekyll

Before publishing, add these two files to this same folder:
- resume.pdf
- cv.pdf

The portfolio already links to those exact filenames. If you publish without them,
the Resume and CV buttons will lead to missing pages.

GitHub Pages setup:
1. Create a new GitHub repository. A name such as temerick.dev is easy to recognize.
2. Upload every file in this folder to the root of the repository.
3. Open repository Settings, then Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the main branch and /(root), then save.
6. In the Custom domain field, enter temerick.dev and save.
7. Update the DNS records at Porkbun as described in the accompanying instructions.
8. After GitHub provisions the certificate, enable Enforce HTTPS.

For later edits, replace index.html or the related asset, commit the change, and
GitHub Pages will publish the new version automatically.
