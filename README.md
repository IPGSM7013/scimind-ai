# SciMind AI — GitHub Pages edition

Interactive science experiments for primary pupils, including 17 laboratories.

## Publish

1. Extract this ZIP on your computer.
2. Create or open your GitHub repository (for example, scimind-ai).
3. Choose Add file > Upload files.
4. Upload index.html, README.md and .nojekyll into the repository root. Upload the extracted files, not the ZIP or its containing folder.
5. Commit the changes.
6. Open Settings > Pages.
7. Choose Deploy from a branch, select main and / (root), then Save.
8. Open the website URL shown by GitHub after deployment completes.

If .nojekyll is hidden by your computer, upload index.html and README.md first. You can create .nojekyll as an empty file using GitHub's Add file > Create new file.

## Included

- index.html: self-contained website with embedded styles, scripts, illustrations and background music.
- .nojekyll: serves the files without Jekyll processing.

## What works in this static edition

The simulations, local lab assistant commands, notes, challenges, sound effects and browser-local progress run in the browser. Sound may require a first click or tap. Progress is stored on the same browser/device and is not synchronized between users.

## Features requiring a separate backend

Cloudflare AI chat uses /api/lab-ai on the hosted application. GitHub Pages cannot provide that endpoint; AI chat will be unavailable here until a compatible backend is configured. The local Arahan makmal assistant remains available. No API keys or server credentials are included.

Teacher/student login, shared class records and dashboards have not been implemented in this edition. GitHub Pages does not add these features automatically.
