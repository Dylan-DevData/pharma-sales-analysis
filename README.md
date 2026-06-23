# Pharmaceutical Sales Data Analysis

Analysis of pharmaceutical sales data using Python, Pandas, and Matplotlib.

## Dataset

Daily sales data from the [Pharma Sales Dataset on Kaggle](https://www.kaggle.com/milanzdravkovic/pharma-sales-data).

Place `salesdaily.csv` inside the `data/` folder before running the script.

## Questions Answered

1. What are the total sales quantities for each drug category (ATC code)?
2. Which drug categories have the highest total sales?
3. Which three drugs have the highest sales in January 2015, July 2016, and September 2017?
4. Which drug was sold most frequently in 2017?
5. Which drug category has the highest average daily sales?
6. Are respiratory drugs (R03) sold more during specific months?

## Project Structure

```
Analysing-pharmaceutical-sales-data/
├── data/
│   └── salesdaily.csv
├── analyse_pharma.py
├── requirements.txt
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Dylan-DevData/Analysing-pharmaceutical-sales-data.git
   cd Analysing-pharmaceutical-sales-data
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download `salesdaily.csv` from Kaggle and place it in the `data/` folder.

4. Run the analysis:
   ```bash
   python analyse_pharma.py
   ```

Charts will be saved automatically in the project folder.

## Technologies

- Python 3
- Pandas
- Matplotlib