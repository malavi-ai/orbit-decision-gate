# ORBIT Decision Gate

Interactive illustration of the **ORBIT** constraint-gated procedure: when should a warning signal lead to **monitoring**, **targeted inquiry** or **corrective action**?

**Open the app:** https://malavi-ai.github.io/orbit-decision-gate/
On a phone or laptop, choose **Add to Home Screen** or **Install** to use it as an app, also offline.

## The three steps

| Step | Question | What the app does |
|---|---|---|
| 1. Screen | Worth reviewing? | Six yes/no warning flags (market, inventory, operations, liquidity, financing, capital). Score = share of observed warnings; withheld if fewer than 4 domains are observable. |
| 2. Decision gate | Is a requirement at risk, and by when? | Headroom = usable capacity − requirement at the due date, for each discrepancy separately and for all together. |
| 3. Response | Which policy costs least? | Compares the expected cost of monitoring, targeted inquiry (cost of the question and of waiting) and immediate action, and selects the lowest. |

Three illustrative cases are included: a joint shortfall, a later cost, and ample headroom.

## Scope

- The tool illustrates the decision logic of a conceptual framework.
- All example values are invented.
- It is **not** an empirically validated model. Where probabilities or costs cannot be defended, a robust rule with stated scenario bounds is preferable to a single expected value.

## Run locally

Open `index.html` in any modern browser. No installation or server is required.

## Files

| File | Purpose |
|---|---|
| `index.html` | The application |
| `manifest.webmanifest`, `sw.js`, `icons/` | Installable app and offline use |
| `CITATION.cff` | How to cite this software |
| `.zenodo.json` | Metadata for the Zenodo DOI |
| `LICENSE` | MIT License |

## Citation

Please cite this software using `CITATION.cff` (the **Cite this repository** button on GitHub). A DOI is issued through Zenodo for each release.

## Author

Seyed Mehdi Alavi · Doctoral School of Regional and Business Administration Sciences, Széchenyi István University, Győr, Hungary · ORCID [0009-0003-8430-211X](https://orcid.org/0009-0003-8430-211X)

## License

Released under the [MIT License](LICENSE).
