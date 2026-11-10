# Pazy Treasury

Three static Pazy Treasury landing-page prototypes.

| Page | Source | Preview |
| --- | --- | --- |
| Unaware audience — original | [index.html](index.html) | [Open original](https://kingviv07.github.io/Pazy-Treasury/) |
| Unaware audience — mobile V2 | [v2.html](v2.html) | [Open mobile V2](https://kingviv07.github.io/Pazy-Treasury/v2.html) |
| Problem-aware audience | [problem-aware.html](problem-aware.html) | [Open problem-aware](https://kingviv07.github.io/Pazy-Treasury/problem-aware.html) |

## Share

Send a **Preview** link above to let anyone view and interact with a page in their browser. No ChatGPT or GitHub login is required to view the public previews.

To share the source code, send this repository URL. To download all files, choose **Code → Download ZIP**. Keep the HTML, CSS, JavaScript and `assets` folder together.

## Run locally

No build or dependencies are required. From the repository folder:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000/`, `http://localhost:8000/v2.html`, or `http://localhost:8000/problem-aware.html`.

## Files

- `index.html`, `style.css`, `app.js`: original unaware page and its interactive preview flow.
- `v2.html`, `v2.css`: mobile-focused styling of the original; same copy and original `app.js` flow.
- `problem-aware.html`, `problem-aware.css`, `problem-aware.js`: problem-aware page.
- `assets/`: local fund, customer and media logos used by the pages.
- `docs/`: design and validation notes.

The original page is preserved. All three versions include their relevant comparison, pricing and signup interactions.

## Prototype scope

Accounts, payments, KYC review and investment actions are simulated. No real payment, document upload, KYC decision or investment occurs. Historical performance figures are dated within the pages; they are not guaranteed or forecasts.
