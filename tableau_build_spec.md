# Tableau build specification
Connect Tableau Public to `data/f1_race_records_illustrative.csv`.

1. Team Points: Team vs SUM(Points), horizontal bars.
2. Driver Leaderboard: Driver vs SUM(Points), sort descending, top 10.
3. Tyre Mix: Tyre_Compound vs COUNT(Record_ID).
4. DNF by Failure Type: filter Finish_Status to DNF; Failure_Type vs COUNT(Record_ID).
5. Season Participation: Season vs COUNT(Record_ID), line chart.
6. Host Country Events: Host_Country vs COUNT(Record_ID).

Dashboard: KPI tiles for record count, finish rate, total illustrative points and DNF count. Add Season, Team and Tyre_Compound filters. Prominently display: “Synthetic illustrative data — not official F1/FIA results.”

This is a build specification, not a prebuilt Tableau workbook.
