# Score_Analysis

A comprehensive data analysis project for analyzing and visualizing score distributions using statistical methods and visualization techniques.

## 📊 Project Overview

This project performs in-depth analysis of score data, including:
- **Data Cleaning & Preprocessing**: Loading and cleaning score data from CSV files
- **Exploratory Data Analysis**: Understanding data distributions and patterns
- **Statistical Testing**: Conducting normality tests, homogeneity of variance tests, and ANOVA
- **Visualization**: Creating multiple visualizations to understand score distributions
- **Statistical Comparisons**: Performing pairwise comparisons using Tukey's HSD test

## 🛠️ Technologies & Libraries

- **Data Processing**: 
  - `pandas`: Data manipulation and analysis
  - `numpy`: Numerical computations

- **Visualization**:
  - `matplotlib`: Plotting library
  - `seaborn`: Statistical data visualization

- **Statistical Analysis**:
  - `scipy`: Scientific computing and statistical tests
  - `statsmodels`: Statistical modeling and hypothesis testing

## 📋 Key Features

- **Normality Testing**: Shapiro-Wilk test for normal distribution
- **Homogeneity of Variance Testing**: Levene's test
- **ANOVA Analysis**: One-way ANOVA for comparing groups
- **Post-hoc Tests**: Tukey's HSD for pairwise comparisons
- **Q-Q Plots**: Quantile-quantile plots for normality assessment
- **Multiple Visualizations**: Histograms, box plots, and distribution plots

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Required packages (see Technologies & Libraries section)

### Installation

Install required packages using pip:
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels
```

### Usage

The analysis is implemented in `score_analysis (1).ipynb` Jupyter notebook. Run cells sequentially to:
1. Load and prepare your score data
2. Perform exploratory data analysis
3. Conduct statistical tests
4. Generate visualizations

## 📁 Project Structure

```
Score_Analysis/
├── README.md                    # This file
├── score_analysis (1).ipynb     # Main analysis notebook
└── Scores.csv                   # Input data file (not included)
```

## 📊 Output

The notebook generates various outputs including:
- Data summaries and statistics
- Statistical test results
- Multiple visualization plots
- Comparison analyses

## 📝 Notes

- Ensure your score data is in CSV format with appropriate column names
- The score column values are expected to use commas as decimal separators and will be converted to float
- Warnings are filtered for cleaner output

## 📧 License

This project is available for educational and analytical purposes.