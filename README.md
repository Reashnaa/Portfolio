# Reashnaa Mohanan — Portfolio Website

A personal portfolio for a Financial Technology student at Republic Polytechnic. Built with plain HTML, CSS and JavaScript, with no paid hosting or build tools required.

## Preview locally

Open `index.html` in your browser. You can also use VS Code's Live Server extension.

## Publish for free with GitHub Pages

1. Sign in to GitHub and create a **public** repository called `reashnaa-portfolio` (or another name).
2. Choose **Add file → Upload files** and upload `index.html`, `styles.css`, `script.js` and the `assets` folder (once it has images). Keep the files at the repository root.
3. Commit the files.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**. Select `main` and `/ (root)`, then save.
6. After GitHub finishes deploying, visit `https://YOUR-GITHUB-USERNAME.github.io/reashnaa-portfolio/`.
7. Test the website on mobile and in a private/incognito window.

GitHub Pages availability and interface can change. Refer to https://docs.github.com/en/pages for current instructions.

## Before sharing with recruiters

- Replace the placeholder portrait in `index.html` with an actual image in `assets/` (see below).
- Replace `REPLACE_WITH_YOUR_EMAIL` in `index.html` with your email address (avoid publishing an address you don't want public).
- Replace `https://www.linkedin.com/` with your real LinkedIn profile URL.
- Review all project, education and achievement information for accuracy.
- Add your resume PDF only when you're comfortable making it publicly downloadable; link it from the website.
- Replace placeholder project summaries with approved, accurate details and your own screenshots.
- Check all links and pages before including the URL in internship applications.

## Add a photograph

Save an image as `assets/portrait.jpg`. In `index.html`, replace the entire `<div class="portrait-inner">...</div>` element with:

```html
<img src="assets/portrait.jpg" alt="Portrait of Reashnaa Mohanan" style="width:100%;height:100%;min-height:492px;object-fit:cover;display:block;" />
```

## Change content and colours

- **Text and sections:** edit `index.html`.
- **Colours, spacing and fonts:** edit `styles.css` (colour variables are at the top).
- **Mobile menu, animations and project popups:** edit `script.js`.
- **Project popup content:** edit the `projects` object in `script.js`.

## Credits and transparency

Initial template was created with AI assistance. Review, customise, test and understand the site before describing your personal contributions to recruiters.


## Updated website layout

- **About Me** now includes a compact education summary (no separate Education section).
- **My FinTech Work** comes next, with five coursework collection placeholders: Python, Tableau, SQL, Excel and Software Application Development. These are intentionally broad descriptions until specific coursework is added.
- **Projects** includes two short cards that link to **separate pages**: `synapse-insure-advisor.html` and `the-focus-frame.html`. Edit those files to add photos, details and reflections later.
- Skills, leadership/international experience, achievements and contact follow afterwards.

When publishing to GitHub Pages, upload **all** the HTML files plus `styles.css` and `script.js` together.

## Tableau coursework project

The Tableau Projects card on the main page links to `tableau-campus-printing.html`. The detail page uses a two-column layout (text on the left, dashboard image on the right) on desktop and stacks vertically on mobile. The original dashboard image is stored at `assets/campus-printing-dashboard.png`; clicking it opens the full-size image.

The campus printing figures were checked against the provided workbook (`Lesson5_Printing_Relationship_Lab_v3.1.xlsx`). The underlying dataset is **not included** in the public website. Confirm that your institution permits sharing the dashboard screenshot before publishing.

## Python HDB resale analysis

The Python Projects card links to `python-hdb-resale-analysis.html`, showing a verified chart from a guided Python/Pandas coursework exercise. The underlying transaction workbook is not bundled. A corrected standalone notebook is provided separately for review.

## Python HDB project: downloadable source and dataset

The Python case-study page includes direct downloads for:
- `downloads/Reashnaa_L14_Exercises_Minimally_Corrected.ipynb` — the lecturer-format notebook with two minimal fixes.
- `downloads/resale-flat-prices-from-jan-2017.xlsx` — the matching exercise dataset.

To reproduce: download both into the same directory; open the notebook in Jupyter or VS Code; install `pandas`, `openpyxl`, `matplotlib`, and `ipykernel` as needed; run all cells; enter `2 ROOM` and `BEDOK` when prompted. The input is case-sensitive in this original-format notebook.

These two downloadable files are bundled with the website. If publishing the workbook publicly, confirm that redistribution is permitted by your lecturer or dataset licence. If not permitted, remove the workbook from `downloads/` and remove its public download link before publishing; provide an approved dataset access route instead.
