# Data Analyst Course

A simple web app that teaches data analysis, starting with Microsoft Excel.

## What it does (version 1)
- One Excel lesson page with an explanation and a downloadable practice `.xlsx` task.
- An upload page where the learner submits their completed `.xlsx` file.
- A checker, written in code, that reads the file and checks the answers — including whether formulas were used instead of typed numbers.

Later versions will add an AI tutor that explains mistakes. Not in version 1.

## Technology
Plain HTML, CSS and JavaScript running in the browser, plus the SheetJS library for reading/writing `.xlsx` files. No server, no build step: open `index.html` in a browser. Python and Node.js are not installed on this machine.

See `PLAN.md` for the full version 1 plan (files, checker rules, build steps, verification).

## Rules for working with me
- I'm a beginner. Before running any terminal command, explain in plain language what it does.
- Explain what you changed after each edit, in simple terms.
- Ask me before adding new files or tools I haven't asked for.
