# CyberPrep — NPTEL Cyber Security & Privacy

A mobile-friendly static quiz website built with HTML, CSS and JavaScript for GitHub Pages.

## Run
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Open repository **Settings → Pages**.
2. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, and Save.
3. Wait for deployment, then open the published Pages URL.

## Import your 120 questions
Use the website's **Download template** button or edit `cyberprep-question-template.json`. The file can be either a JSON array or an object with a `questions` array. Each question needs:
- `question`: question text
- `options`: answer options
- `answer`: zero-based index (0 means the first option) or exact option text
- `topic`, `explanation`, and `id`: optional

The website currently has three sample questions only. Import your own question bank to use your actual assignment/practice questions.

## Notes
Progress and imported questions are saved in this browser's localStorage. They do not sync across devices. Keep a backup of your JSON question bank. CyberPrep is an independent study aid, not an official NPTEL website.
