dirty CSVs -> validation + quarantine -> cleaned tables
           -> star schema + KPI tables (SQL) -> Streamlit dashboard
                                             -> Power BI CSVs + Excel summary

                                             
## Questions it answers

1. How often are patients readmitted within 30 days, and in which departments?
2. Which patient groups readmit more (age, payer, chronic conditions, earlier stays)?
3. Where is bed capacity used, and which long stays block it?
4. Where is revenue lost (claim denials, collections, drug cost differences)?


## Dashboard tabs

| Tab | What it shows |
|---|---|
| Executive Summary | Main KPIs, monthly volume, readmission rate by department |
| Readmission Drivers | Age, payer, chronic conditions, time to readmission |
| Capacity & LOS | Bed-days, average stay, long-stay outliers |
| Revenue Cycle | Billed vs collected, denial reasons, drug cost spread |
| Data Quality | Rule results, issue severity, flagged records |
