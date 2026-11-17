# plp-da-a2-rainfall-advisory

## Project summary
This project cleans hand-typed monthly rainfall data for the Machakos weather station, combines it with readings from Nairobi, Nakuru, Kisumu and Mombasa, and uses NumPy to find annual totals, wettest months, dry months and the best two-month planting window for each county. The results are saved to `rainfall_summary.csv` and used to write a short planting advisory for a farmer-support NGO.

## How to run
[Open in Colab](https://colab.research.google.com/github/Alice34mung3ai/plp-da-a2-rainfall-advisory/blob/main/rainfall_analysis.ipynb)

Click the link and choose **Runtime → Run all**. No installs needed.
## Planting advisory
- Farmers in Nairobi, Nakuru, Kisumu and Mombasa should plant in April–May, the wettest two-month window in all four counties.
- Machakos farmers should plant in November–December for the short rains, and use drought-tolerant crops because the county has 6 dry months.
- Two Machakos months (April and September) were missing in the raw data and were estimated at 68 mm, so Machakos advice should be checked against the station records.
