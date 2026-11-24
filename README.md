# MB-330 Field Kit

A one-file study app for MB-330 (Dynamics 365 Supply Chain Management Functional Consultant).

- `index.html` is the whole app. Open it in a browser, or host it anywhere.
- Progress is saved in each person's browser (localStorage). Use Progress > Backup to move it.

## Put it on GitHub Pages
1. Create a new public repository on GitHub, e.g. `mb330-field-kit`.
2. Upload `index.html` to the root (Add file > Upload files > Commit).
3. Settings > Pages > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` > Save.
4. After a minute the site is at `https://<your-username>.github.io/mb330-field-kit/`.

## Edit the content
All content is in the `<script>` block: `DOMAINS`, `CARDS`, `QUESTIONS`, `LABS`.
Topics follow Microsoft's MB-330 skills outline (Oct 21, 2026). Explanations and questions were written by Claude from general knowledge, not copied from Microsoft or real exams. Cards marked "check this" should be verified on Microsoft Learn first.
