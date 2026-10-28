# Formula 1 Race Intelligence Dashboard (2010–2026)

Interactive portfolio demo with filters for season, team and tyre compound; KPI cards; team and driver point leaderboards; tyre mix; DNF categories; and season participation.

**Data disclosure:** `data/f1_race_records_illustrative.csv` contains 6,464 synthetic illustrative rows, not official Formula 1/FIA results. Do not present the values as factual race outcomes. Replace with a verified public dataset before making real-world claims.

## Files
- `dashboard/index.html`: interactive browser demo
- `data/f1_race_records_illustrative.csv`: illustrative dataset
- `data_dictionary.md`: field meanings
- `tableau_build_spec.md`: Tableau worksheet and dashboard plan
- `project_summary.md`: project overview

## Demo deployment
For the simplest GitHub Pages URL, copy `dashboard/index.html` to the repository root and name it `index.html`. Upload the project files to a public repository, then go to Settings → Pages → Deploy from a branch → `main` → `/(root)`. After deployment, URL format is `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

The HTML demo is separate from a published Tableau workbook. The Tableau spec is a guide, not a prebuilt workbook.
