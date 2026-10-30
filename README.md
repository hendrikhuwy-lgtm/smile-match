# Smile Match

A five-question toothpaste colour quiz for an orientation booth. A tooth buddy reacts to each answer, then reveals one clear match (Purple for whitening, Blue for sensitivity, Green for all-round care) with a booth pass and a shareable colour card.

**Live:** https://hendrikhuwy-lgtm.github.io/smile-match/

Smile Match is a student concept prototype. It is not affiliated with any toothpaste brand.

## How it works

- One static page, `index.html`, with no build step, no backend and no tracking.
- Answers stay in the visitor's browser. The last result is kept in local storage until someone taps New Student.
- On a phone the app fills the screen. On a wide screen it sits inside a glass phone frame.

## Scoring

Each answer counts as one vote for its colour, and the majority wins. Five answers over three colours can only tie 2–2–1. A tie goes to the answer to question 1 (biggest concern). If that answer is the odd one out, question 5 (what matters most) decides. Every colour wins exactly 81 of the 243 possible answer sets.

## Updating

Replace `index.html`, commit and push to `main`. GitHub Pages redeploys in about a minute.
