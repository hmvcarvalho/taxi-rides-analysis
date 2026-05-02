# Taxi Rides Analysis

Exploratory data analysis of taxi rides in Chicago.

## Setup

1. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```

2. Activate it (Windows):
   ```bash
   .venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Project Structure

- `EDA.ipynb` — exploratory data analysis notebook
- `data/` — SQL query results used as input for the analysis
  - `trips_by_company.csv` — number of trips per taxi company
  - `avg_trips_by_dropoff_neighborhood.csv` — average trips per dropoff neighborhood
- `requirements.txt` — project dependencies
