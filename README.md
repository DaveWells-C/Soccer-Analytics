# Soccer-Analytics

(11/22/26)
# Orange County SC — 2026 USL Championship Analytics

A Python data-analysis project exploring **Orange County SC's** 2026 USL Championship performance, positional production, and expected goals (`xG`).

## Repository Contents
* **`notebooks/`** — Google Colab notebooks covering data cleaning, per-90 efficiency, positional `.groupby()` breakdowns, and `xG` visualizations.
* **`data/raw/`** — Unmodified CSV exports from FBref.
* **`data/processed/`** — Cleaned leaderboards and positional summary tables ready for visualization.

## Key Week 1 Findings
* **Positional Output:** Forwards led the squad in `Goals_per_90` and overall `Goal_Share_Pct`, while midfielders anchored total minutes played.
* **Efficiency Filtering:** Filtering for **600+ minutes** isolated true regular contributors from small-sample sub appearances.

## Tools Used
* **Python 3** & **`pandas`** (data cleaning, filtering, vectorized metrics, `.groupby()`)
* **Google Colab** (interactive notebooks)
* **Data Sources:** FBref & American Soccer Analysis (`itscalledsoccer`)
