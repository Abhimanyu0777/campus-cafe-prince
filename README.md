# ☕ Campus Café — Open Source Cohort Selection Test

A small static website made with **HTML and CSS only**. Every page has a few bugs. Your job is to fix **the one issue assigned to you**.

## Run it
Open `index.html` in your browser (or use the VS Code *Live Server* extension).
Tip: use DevTools (F12) and the device toolbar to test narrow screens.

## Rules
1. Work **only** on the issue assigned to you. Do not fix other bugs, even if you spot them.
2. Change only what is needed. Do not reformat files or rename things.
3. Don't use `!important` unless the issue says it is allowed.
4. Submit your own work. PRs are reviewed line by line.

## Workflow
```bash
# 1. Fork this repo on GitHub, then clone YOUR fork
git clone https://github.com/<your-username>/campus-cafe.git
cd campus-cafe

# 2. Create a branch named after your issue
git checkout -b fix/issue-<number>

# 3. Fix the bug, test it in the browser, then
git add .
git commit -m "Fix #<number>: short description"
git push origin fix/issue-<number>

# 4. Open a Pull Request to the original repo. Write "Fixes #<number>" in the description.
```

## Project structure
```
index.html        home page (lists all menu pages)
<page>.html       one file per menu page (18 pages)
css/base.css      shared styles
css/<page>.css    styles for that page
images/           illustrations
```
