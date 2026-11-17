# plp-da-a2-rainfall-advisory

## Project summary
This project cleans hand-typed monthly rainfall data for the Machakos weather station, combines it with readings from Nairobi, Nakuru, Kisumu and Mombasa, and uses NumPy to find annual totals, wettest months, dry months and the best two-month planting window for each county. The results are saved to `rainfall_summary.csv` and used to write a short planting advisory for a farmer-support NGO.

## How to run the notebook
1. Clone the repository and open a terminal in the project folder.
2. Install the requirements: `pip install -r requirements.txt` (the notebook also needs Jupyter, e.g. `pip install notebook`).
3. Start Jupyter with `jupyter notebook`, open `rainfall_analysis.ipynb`, and choose **Kernel > Restart & Run All**. Running it regenerates `rainfall_summary.csv`.

## Planting advisory
- Farmers in Nairobi, Nakuru, Kisumu and Mombasa should plant in April–May, the wettest two-month window in all four counties.
- Machakos farmers should plant in November–December for the short rains, and use drought-tolerant crops because the county has 6 dry months.
- Two Machakos months (April and September) were missing in the raw data and were estimated at 68 mm, so Machakos advice should be checked against the station records.
