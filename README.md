# AAPL Stock Analysis and Data Visualization

## About the Project

This project analyzes **Apple (AAPL) stock data** using Python. The dataset contains stock information such as Date, Open, High, Low, Close, and Volume.

The project cleans the data, calculates daily price changes and returns, studies trading volume, finds unusual trading days, and analyzes the stock return distribution.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

## Dataset

The dataset contains the following columns:

* Date
* Open
* High
* Low
* Close
* Volume

## Work Done

### 1. Data Cleaning

* Converted the Date column into date format.
* Converted stock price and volume columns into numeric values.
* Removed missing values.
* Sorted the data by Date.

### 2. Price Analysis

Calculated the **Price Delta**:

`Price Delta = Close - Open`

Calculated the **Daily Return**:

`Daily Return = ((Close - Open) / Open) × 100`

### 3. Trading Volume Analysis

* Calculated the average trading volume.
* Created a trading volume trend graph.
* Used mean and standard deviation to identify anomalous trading days.
* Displayed the anomaly limit on the graph.

### 4. Return Distribution

A histogram was created to understand the distribution of daily stock returns.

The following statistical measures were calculated:

* Mean
* Variance
* Standard Deviation

## Output

The project produces:

* Cleaned AAPL stock dataset
* Price Delta
* Daily Return
* Trading Volume Trend graph
* Anomalous Trading Days
* Volume Anomaly graph
* Daily Return Distribution histogram
* Return statistics

The cleaned dataset is saved as:

`AAPL_cleaned.csv`

## Files

```text
AAPL-Stock-Analysis/
│
├── DV_TASK_3.ipynb
├── dv_task_3.py
├── AAPL.csv.xls
├── AAPL_cleaned.csv
└── README.md
```

## How to Run

1. Open the notebook in **Google Colab** or Jupyter Notebook.
2. Upload the AAPL dataset.
3. Run the Python cells step by step.
4. View the graphs and statistical results.
5. The cleaned dataset will be saved as `AAPL_cleaned.csv`.

## Conclusion

This project helps to understand AAPL stock price movements, daily returns, trading volume trends, unusual trading days, and return distribution using simple Python data analysis and visualization techniques.

## Author

**Brajesh Sheguware . K**
