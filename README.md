# Market Case Studies

Dated write-ups of big market moves: what happened, scenarios with odds, and a scorecard when the results come in.

| # | Date | Case study | Scorecard |
|---|---|---|---|
| 01 | 29 Sep 2026 | [The Rule Was the Moat (FICO)](fico/) | Due after FICO's FY Q4 report, Nov 2026 |

For learning, not investment advice.

---

## Publishing with GitHub Pages (one-time setup)

1. On GitHub, create a new **public** repository named `case-studies`.
2. Click **Add file → Upload files** and drag in everything from this folder: `index.html`, `README.md`, `.nojekyll`, and the `fico` folder. Commit.
3. Go to **Settings → Pages**. Under "Build and deployment", pick **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. After a minute or two the site is live at `https://<your-username>.github.io/case-studies/`, and the FICO page at `.../case-studies/fico/`.

## Adding the next case study

1. Make a new folder named after the ticker or topic (for example `nvda/`) containing an `index.html`.
2. Add an entry to the list in `index.html` and a row to the table above.
3. When a scorecard is due, add a "Scorecard" section to that page. Don't edit the original scenarios; the commit history shows what was written and when.
