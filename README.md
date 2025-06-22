
# Bank Customer Data Real-Time Dashboard

This Streamlit app provides a real-time dashboard for analyzing bank customer data. Users can filter by job type and view key performance indicators (KPIs) such as average age, number of married customers, and average account balance. The dashboard also features interactive visualizations and a detailed data table.

## Features

- Filter data by job type
- View KPIs: average age, married count, and average balance
- Bar plot of age by marital status
- Histogram of age distribution
- Detailed data table

## Tech Stack

- Python
- Streamlit
- Pandas
- Seaborn
- Matplotlib

## Getting Started

1. **Install dependencies:**

   ```sh
   pip install -r requirements.txt
   ```

2. **Place your data:**

   Ensure `bank.csv` is in the [`bank/`](bank/) directory.

3. **Run the app:**

   ```sh
   streamlit run app.py
   ```

   (Run this command from the [`bank/`](bank/) directory.)

## File Structure

- [`bank/app.py`](bank/app.py): Main Streamlit dashboard application
- [`bank/bank.csv`](bank/bank.csv): Bank customer dataset
- [`bank/requirements.txt`](bank/requirements.txt): Python dependencies

## Example

![Dashboard Screenshot](https://user-images.githubusercontent.com/your-screenshot.png)

---

*Developed for real-time data analysis and visualization of bank customer
