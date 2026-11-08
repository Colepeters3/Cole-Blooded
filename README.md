# 🔥 COLE BLOODED — A Courtroom Showdown

A free, browser-based interactive courtroom game featuring **Harvey Specter** and **Mike Ross**. Play as the judge: select a case (or roll a random one), introduce and rule on evidence, hear opposing arguments, decide the verdict, choose a mid or high consequence, and see the winner.

## Play online

After enabling GitHub Pages, the game will be available at:

`https://YOUR-USERNAME.github.io/cole-blooded/`

Replace `YOUR-USERNAME` with your GitHub username and `cole-blooded` with your chosen repository name.

## Run locally

Download or clone the repository and open `index.html` in any modern browser. No installation, account, server, API key, or build command is needed.

## Deploy on GitHub Pages

1. Sign in to [GitHub](https://github.com/) and create a **public** repository named `cole-blooded`.
2. Select **Add file → Upload files** and upload `index.html`, `README.md`, and `.nojekyll` from this project, then commit the files.
3. Open the repository’s **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then click **Save**.
6. Visit `https://YOUR-USERNAME.github.io/cole-blooded/` once GitHub Pages finishes deploying. The URL also appears in the Pages settings.

### Updating the live game

Replace `index.html` with your updated version and commit the change. GitHub Pages will publish the new version.

## Features

- 12 fictional cases, including balanced and deliberately difficult scenarios
- Choose a specific case or start a random trial
- Harvey and Mike randomly switch sides between trials
- Admit or exclude exhibits; introduce three new evidence options or your own
- Hear simulated arguments, manage objections, issue directions, and call for closings
- Submit a verdict, choose mid/high sentencing or remedy, and see the winner
- Responsive interface; no external JavaScript dependencies

## Note on AI and imagery

This is an **offline, scripted simulation**, not a generative AI service. Dialogue is generated from local case and evidence templates. Character portraits in this version are the existing **emoji illustrations**; this package does not add actor photographs or copyrighted TV publicity images.

All cases are fictional. Game odds are narrative difficulty settings, not actual legal probabilities or legal advice.

## Pretrial jury selection

After choosing a case, manually fill three jury seats. Click a seat to target it, then select any juror. Duplicate selections are allowed, including the same juror in all three seats. Begin trial unlocks only when all three seats are filled. Starting another case clears the seats.

The searchable roster contains 200 deterministic fictional adults, with age, gender, occupation, education, city, relationship to law enforcement, and self-described race. Each card has a locally generated SVG illustration. Appearance is varied independently of demographics. These attributes do not affect trial outcomes. Expand “Seated jury” during trial to review your selections.

The full dataset is also included as jurors.json for reference. The standalone HTML embeds its own generator and requires no other files or network connection.
