# RACI Matrix Builder for Cross-Functional Projects

An interactive, single-file tool that helps teams define **who is Responsible, Accountable, Consulted, and Informed** for each task — and catches governance gaps in real time.

**[Live demo →](https://upasanasen.github.io/raci-matrix-builder/)**

## The problem

Cross-functional projects fail predictably when ownership is unclear. Two people think they're driving the same decision. A task has five "owners" but no one is actually accountable when it slips. Most teams either skip RACI (too much friction) or build one that's quietly broken.

## What this tool does

- **Editable matrix** — add tasks (rows), add roles/people (columns), assign R / A / C / I with a click
- **Live validation** as you type, flagging:
  - Tasks with no Accountable owner
  - Tasks with multiple Accountable people (RACI requires exactly one)
  - Tasks with no Responsible doer
  - Too many Consulted parties (slows decisions)
  - One person carrying too much accountability (single point of failure)
- **Summary stats** — coverage %, R/A/C/I totals, tasks-with-Accountable count
- **Exports** — CSV, JSON, and print-to-PDF with a clean print stylesheet
- **Sample project preloaded** so the tool demonstrates itself the moment it opens

## How to use it

1. Open the [live demo](https://upasanasen.github.io/raci-matrix-builder/)
2. Click **Clear All** and add your real tasks and people
3. Click R / A / C / I cells to assign roles (click again to clear)
4. Watch the validation panel — those are the conversations your team needs to have
5. Export to CSV or print to PDF for your project charter

## Run locally

It's a single self-contained HTML file. Clone the repo and open `index.html` in any browser. No build step, no dependencies, no data leaves the browser.

## License

MIT — see [LICENSE](LICENSE).
