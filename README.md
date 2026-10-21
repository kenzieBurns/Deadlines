# Deadline Board

Paste your scattered assignment notes and get a board that shows:

- a countdown to your next hand-in
- crunch-week warnings when several deadlines land close together
- a six-week calendar, colour-coded by how close each deadline is
- every deadline grouped by urgency, with "Submitted" ticks
- how each module is weighted, plus quiz scores

It's one static `index.html` file with no build step and no server. Each visitor's board is saved in their own browser (localStorage). To move a board to another device, use the copy-link or backup buttons in the editor.

**Converting notes:** a built-in rule-based converter pulls out dates, times, percentages and quiz scores. You check the results in an editable table before saving. If you have an Anthropic API key, you can use the optional "Convert with AI" button instead. It sends your notes from your browser straight to the Anthropic API, and the key is stored only in your browser.

## Run locally

Open `index.html` in a browser.

## Deploy

This is hosted with GitHub Pages. In the repo, go to **Settings → Pages** and choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
