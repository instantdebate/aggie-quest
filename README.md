# Aggie Quest

A mobile-friendly, no-build GitHub Pages checklist for fall 2027 Texas A&M freshman applications at College Station. Open index.html to preview on a computer, or publish with the steps below.

## Publish on GitHub Pages

1. Sign into GitHub and create a new repository named `aggie-quest`. On a free account, a public repository is the straightforward Pages option.
2. Unzip this package on your computer (or in the iPhone Files app).
3. In the repository, choose **Add file → Upload files**. Upload `index.html`, `GUIDE.md`, and `README.md` directly into the repository root. Do not upload the ZIP or nest the files inside another folder. Optionally upload `.nojekyll` too.
4. Commit the files to the `main` branch.
5. Open repository **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, then `main` and `/ (root)`, and save.
7. When GitHub reports deployment complete, open the Pages URL shown there. Its usual format is `https://YOUR-USERNAME.github.io/aggie-quest/`.
8. Open the URL on her phone. In Safari, use **Share → Add to Home Screen** if desired.
9. Complete one quest, reload, and confirm the checkmark survives. Export a backup before switching browsers or devices.

If using an iPhone, GitHub’s desktop website view may make Settings and uploads easier to find. A computer is usually simpler for the initial upload. No terminal, npm, build command, API keys, or database is required.

## Features

- 23 bite-size quests, with conditional ApplyTexas, top 10%, engineering, and after-admission steps.
- XP, progress, levels, and milestone badges.
- A next-action card, phase filters, unfinished filter, notes, and printing.
- Browser-local storage, JSON backup/restore, reset confirmation.
- Official links and a detailed guide.

## Important behavior

Progress is local to a browser and URL origin. It does not synchronize across devices or notify parents. Opening a local file and later using the published URL can result in different storage; use backup/restore to transfer progress. Private browsing and clearing browser data can remove progress. Browser storage failures display a warning.

A public Pages site makes the generic checklist and source visible to everyone. Your checkmarks and notes are not sent to a server by this app. Do not put personal documents, credentials, IDs, essays, or sensitive notes in the repository or app. Backup files contain the notes you enter; keep backups private.

Checkboxes are self-reported. The app cannot inspect AIS, submit an application, or verify admission status. The weekly reminder task asks you to set a calendar reminder; it does not schedule notifications. Conditional tasks are retained if toggled off and on, but hidden tasks do not affect the active score.

## Update

Edit `index.html` and commit to main. GitHub Pages republishes after its deployment finishes. Requirements were reviewed October 13–14, 2026. Recheck official requirements for another cycle; this is not a rolling admissions calendar.

## Validation

JavaScript syntax and logic checks cover settings, active task selection, backup validation, completion scoring, and safe text rendering. No browser visual test was performed in this environment.
