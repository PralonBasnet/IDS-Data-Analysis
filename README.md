# IDS-Data-Analysis

A data analysis project using Python and Jupyter Notebook to identify and classify 
normal vs malicious network traffic from an intrusion detection dataset.

## What it does

- Loads and filters a network traffic dataset to 16 key features
- Cleans data by removing null values and duplicate records
- Performs statistical analysis including correlation matrix, 
  descriptive statistics, skewness, and kurtosis
- Conducts Welch's t-test to determine if attack traffic significantly 
  differs from normal traffic in flow duration
- Visualises class distribution and feature comparisons using 
  bar charts, pie charts, and box plots

## Tech stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data loading and cleaning |
| NumPy | Numerical computation |
| SciPy | Statistical testing (Welch's t-test) |
| Matplotlib | Data visualisation |
| Jupyter Notebook | Interactive analysis environment |

## Dataset

Network intrusion detection dataset with features including flow duration, 
packet length, port numbers, and traffic labels (Normal Traffic / Attack).

## Key findings

- Performed Welch's t-test on Flow Duration between normal and attack traffic
- Identified top correlated feature pairs using Pearson correlation matrix
- Visualised significant differences in packet behaviour between traffic classes

## Running locally

1. Install dependencies
```bash
   pip install pandas numpy scipy matplotlib jupyter
```
2. Update the dataset path in cell 2 to your local CSV location
3. Run all cells in order
