# Annuity Blaster — Finance Challenge

A self-contained browser learning game for Diploma in Accounting students. No backend, login, external assets, build tools, or dependencies.

## Play locally

Open `index.html` in a modern browser. Keep `index.html`, `style.css`, and `script.js` in the same folder.

## Publish on GitHub Pages

1. Create a new public GitHub repository (for example, `annuity-blaster`).
2. Upload **all three website files** (`index.html`, `style.css`, `script.js`) and optionally this README to the repository root.
3. Open the repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)** and save.
5. After GitHub finishes deployment, open `https://YOUR-USERNAME.github.io/annuity-blaster/` (replace the username and repository name).

## Learning design

- 12 questions, including a new final transfer scenario.
- Topics: ordinary annuities, annuities due, future value, present value, periodic rates, and financial interpretation.
- Click/tap moving targets or use number keys 1–4. Pause motion when needed.
- Untimed. 10 points for a first-attempt correct answer, 5 points after a retry. Speed has no effect.
- Incorrect choices are removed for that question and a hint appears; students can try again.
- Correct answers display an explanation and a Continue button.
- Results show first-try accuracy separately from points and give a full explanation review.

## Edit the questions

Open `script.js` and edit `QUESTION_BANK` at the very top. Each entry needs `type`, `question`, four `options`, `answer` (zero-based index 0–3), `explanation`, and `hint`. The total number of questions and maximum score update automatically. For question 7, edit the final corrected options and explanation immediately below the bank, or move those corrected values directly into the question object and remove the override lines.

## Accessibility and privacy

Mouse, keyboard, and touchscreen controls are supported. Respects reduced-motion operating-system settings. There is a manual movement pause control. The game stores no student data and makes no network requests.

## Scope

Questions are an original general introduction to annuities, not transcribed from a particular course handout. If your class uses a specific formula sheet, check its conventions before assigning the game.
