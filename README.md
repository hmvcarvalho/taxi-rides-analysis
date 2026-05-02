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
  - `project_sql_result_01.csv` — number of trips per taxi company
  - `project_sql_result_04.csv` — average trips per dropoff neighborhood
- `requirements.txt` — project dependencies
