# Farzana Faiza portfolio, Version 1

Plain HTML and CSS. No installs, no build tools, no paid services.

## What is in this folder
- `index.html`: homepage with the featured work list and contact links
- `about.html`: background, interests, experience, resume link
- `projects/beyond-behavioral-metrics.html`: your research methodology case study, built from your notes (edit freely)
- `projects/gtri-research.html`, `projects/neuroscience-research.html`, `projects/nonprofit-audit.html`: case study templates
- `style.css`: the only stylesheet. Colors, fonts and widths are at the very top.
- `assets/`: your screenshots, charts and `resume.pdf` go here

## Publish on GitHub Pages
1. Unzip this folder on your computer.
2. On github.com click **+**, then **New repository**. Name it exactly `USERNAME.github.io` (replace USERNAME with your GitHub username). Keep it **Public** and create it.
3. In the new repository click **Add file**, then **Upload files**. Do not upload the .zip itself, because GitHub cannot unpack it. Open the unzipped folder, press **Ctrl+A** (Windows) or **Cmd+A** (Mac) to select everything inside it, and drag it all into the window at once, folders included. Use Chrome, Edge or Firefox, since Safari can skip folders. Wait for the uploads to finish, then click **Commit changes**. `README.md` is only for you, so you can leave it out.
4. Go to **Settings**, then **Pages**. Under Build and deployment choose **Deploy from a branch**, pick branch **main** and folder **/ (root)**, then **Save**.
5. Wait 1 to 3 minutes and open `https://USERNAME.github.io`.

All links are relative, so the site also works if the repository has a different name (the address then ends in `/REPONAME/`).

## Edit text in your browser
1. Open the file on GitHub and click the **pencil** icon.
2. Use **Ctrl+F** (Windows) or **Cmd+F** (Mac) to search for `[ADD`, `[INSERT` or `[CONFIRM`. Every yellow placeholder contains one of these.
3. Type your real text over the placeholder, including the square brackets. Do not change anything inside `< >` symbols.
4. Remove the yellow highlight: if you see `<span class="ph">your text</span>`, delete the `<span class="ph">` and `</span>` pieces. If you see `<p class="ph">`, change it to `<p>`.
5. Click **Commit changes**. The live site updates in 1 to 2 minutes.

## Common changes
- **Colors, fonts, widths:** edit the block at the top of `style.css`.
- **Add an image:** upload it to `assets/` (open that folder, **Add file**, **Upload files**). In the case study, delete the grey placeholder `div` and use the `<img>` line shown in the comment beside it. Always write real alt text.
- **Resume:** upload your PDF to `assets/` and name it `resume.pdf`.
- **Email and LinkedIn:** edit the Contact section in `index.html`.
- **Reorder or hide a project:** each project in `index.html` sits between `ROW START` and `ROW END` comments. Cut and paste a block to reorder. To hide one, add the word `hidden` inside its tag: `<li class="row">` becomes `<li class="row" hidden>`. Remove the word to show it again.

## Add a fourth case study
1. On GitHub open `projects/nonprofit-audit.html` and click the **Copy raw file** icon.
2. Open the `projects` folder, click **Add file**, then **Create new file**. Name it `projects/your-project-name.html` (lowercase, hyphens, no spaces). Paste, and commit.
3. Open your new file and edit: `<title>`, the `description` line, the `<h1>`, the summary under it, the "Before you publish" box, the "At a glance" box, and every section.
4. Open `index.html`, copy one whole project (from `ROW START` to `ROW END`), paste it after the last one, and change the link (`projects/your-project-name.html`), status labels, title, summary, what you investigated, your role and methods.
5. Optional: add a line for it in the Experience list in `about.html`.
6. Commit, wait a minute, and click the new project to check that it opens and that Back to all work returns you home.

## Content rules this template follows
Placeholders are yellow and clearly labeled. Findings (what the evidence showed) are kept apart from interpretation, recommendations and verified outcomes. Do not add results, numbers, quotes or outcomes you cannot back up. Check what GTRI, your lab and the nonprofit allow you to share.

## Before you announce the site: checklists
**Links**
- [ ] Click every menu link on every page (Work, About, Contact) and the Resume link on the homepage
- [ ] Open all four case studies from the homepage, and from About
- [ ] "Back to all work" works on each case study
- [ ] The resume link opens your PDF, and the email link opens your mail app

**Mobile**
- [ ] View on a phone or make the browser window very narrow
- [ ] Nothing scrolls sideways; text is readable without zooming
- [ ] Menu links and cards are easy to tap

**Accessibility**
- [ ] Press Tab through each page: a visible outline always shows where you are
- [ ] The "Skip to main content" link appears on first Tab
- [ ] Zoom to 200 percent: nothing overlaps or disappears
- [ ] Every image has meaningful alt text; each page has one main heading
- [ ] No yellow placeholders remain on pages you are sharing
