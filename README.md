# ORBIT Decision Gate

Interactive illustration of the **ORBIT** constraint-gated procedure: when should a warning signal lead to **monitoring**, **targeted inquiry** or **corrective action**?

**Open the app:** https://malavi-ai.github.io/orbit-decision-gate/
On a phone or laptop, choose **Add to Home Screen** or **Install** to use it as an app, also offline.

## The three steps

| Step | Question | What the app does |
|---|---|---|
| 1. Screen | Worth reviewing? | Six yes/no warning flags (market, inventory, operations, liquidity, financing, capital). Score S = share of observed warnings; withheld if fewer than 4 domains are observable. **Referral rule:** refer to the gate when S ≥ ⅔ (4 of 6, 4 of 5 or 3 of 4). |
| 2. Decision gate | Is a requirement at risk, and by when? | Usable resources = cash + operating inflows + credit, where credit counts only if usable before the due date (30- and 90-day horizons). Headroom = usable resources − requirement, for each discrepancy separately, in the **base case**, and in an **adverse case** with operating inflows reduced by 20%. |
| 3. Response | Monitor, inquire or act? | **Protocol rule (Table 3):** positive headroom in both cases → Monitor; positive in the base case but negative in the adverse case, or evidence incomplete → Targeted inquiry; negative in the base case → Compare interventions. An expected-loss comparison (Section 3.10) is shown alongside. |

Four illustrative cases are included: credit that arrives too late (A), credit in time (B), a thin margin (C) and a joint shortfall (D).

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
| `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` | Installable app and offline use |
| `CITATION.cff` | How to cite this software |
| `.zenodo.json` | Metadata for the Zenodo DOI |
| `LICENSE` | MIT License |

## Citation

Please cite this software using `CITATION.cff` (the **Cite this repository** button on GitHub). A DOI is issued through Zenodo for each release.

## Author

Seyed Mehdi Alavi · Doctoral School of Regional and Business Administration Sciences, Széchenyi István University, Győr, Hungary · ORCID [0009-0003-8430-211X](https://orcid.org/0009-0003-8430-211X)

## License

Released under the [MIT License](LICENSE).
