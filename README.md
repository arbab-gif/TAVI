# TAVI by JUNEX — Product & Experience Design

Design work for **TAVI**, a screenless wearable band + companion app that helps people
*read their body and remember their day*. Four pillars: **Day · Body · Capture · Ask**.

> Tagline: **"Read your body. Remember your day."**

## Contents

### `prototype/`
- **`tavi-app.html`** — interactive, high-fidelity app prototype (a single self-contained
  page, no build step). Opens on the **Day** screen and navigates all four tabs
  (Day · Body · Capture · Ask) with Profile in the top corner.
  - One fictional user (**Layla Haddad**) with clearly-labelled **sample data**.
  - Mandated **Day** order: rings → insight → vitals + HRV → follow-through.
  - **Light / dark parity** (opens in the minimal-futuristic dark theme; toggle in the top bar).
  - A **Learning-state** toggle demonstrates the baseline-learning empty state (`--` / Learning).
  - Honours the product rules: no activity pause, HRV permanent on Day, an Arabic answer
    rendered inside the English-only Ask interface.

  Open it locally by double-clicking, or serve the folder and browse to it.

### `components/`
Progress-indicator explorations authored as Claude Design canvas artboards (`*.dc.html`),
plus `canvas.json` (layout) and `tavi-progress-rings.html` (the published canvas bundle).

- **Directions:** `Main` (dominant Core + satellites), `Concentric` (single dial), `Linear` (tracks).
- **Progress circles:** `CircleRow` (equal row), `CircleStacked` (compact list), `CircleTriad`
  (gradient tapered triad).

## Design direction
Premium, minimal, futuristic. Black/white foundation on warm Yas Marina neutrals; colour is
used only to encode ring state — **Core** amber `#E2AB61`, **Recovery** sage `#7CC2A3`,
**Sleep** periwinkle `#8E93C8`. Type: **Sora** (display) + **Hanken Grotesk** (UI).

Sample data is illustrative and clearly labelled; it is not real account data.
