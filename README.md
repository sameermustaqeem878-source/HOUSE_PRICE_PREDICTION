
# California Housing Prices – Exploratory Data Analysis

An Exploratory Data Analysis (EDA) project focused on understanding housing prices across California using the California Housing Prices dataset.

The project uses Python to inspect, clean, and visualize housing data, exploring how geographical location, population, housing characteristics, and ocean proximity relate to median house values.

## Project Overview

| Detail | Description |
|---|---|
| Dataset | California Housing Prices |
| Source | [Kaggle Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices) |
| Original Records | 20,640 |
| Features | 10 |
| Target Variable | `median_house_value` |
| Environment | Google Colab / Jupyter Notebook |

## Key Features

- Downloading the dataset using KaggleHub.
- Inspecting dataset structure and data types.
- Checking missing values and duplicate records.
- Analyzing the distribution of housing prices.
- Identifying values capped at the maximum price of $500,001.
- Removing capped target values for further analysis.
- Exploring geographical housing price patterns.
- Comparing house values across ocean proximity categories.
- Analyzing correlations between numerical features.
- Exporting the cleaned dataset for future machine learning tasks.

## Data Cleaning

The original dataset contains 20,640 records and 10 features.

The preprocessing stage includes:

1. Inspecting missing values, including missing entries in `total_bedrooms`.
2. Checking duplicate records.
3. Identifying the maximum target value of `$500,001`.
4. Finding 965 records where the median house value reaches this upper limit.
5. Removing records with capped target values from the cleaned dataset.
6. Exporting the resulting dataset as `housing_clean.csv`.

Removing capped target values helps avoid treating the dataset's price ceiling as an accurate representation of actual higher property values.

## Exploratory Data Analysis

### 1. Feature Distributions

Histograms are used to examine the distribution of numerical features and understand the spread of housing and demographic data.

### 2. Geographical Analysis

Scatter plots using longitude and latitude help visualize housing prices across California.

Population information is also used to provide additional context about the geographical distribution of housing records.

### 3. Ocean Proximity Analysis

Box plots compare median house values across different `ocean_proximity` categories to examine how location relates to property prices.

### 4. Feature Correlation

Horizontal bar charts display the linear correlation between numerical features and `median_house_value`.

This helps identify which numerical variables have stronger relationships with the target.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical graphics |
| KaggleHub | Dataset downloading |
| Jupyter Notebook | Development environment |
| Google Colab | Cloud-based execution |

## Project Structure

```text
housing_project/
│
├── notebook.ipynb
├── housing_clean.csv
├── distributions.png
└── exploration.png
```

| File | Description |
|---|---|
| `notebook.ipynb` | Complete data cleaning and EDA pipeline |
| `housing_clean.csv` | Cleaned dataset with capped target records removed |
| `distributions.png` | Histograms of numerical feature distributions |
| `exploration.png` | Geographical analysis, box plots, and correlation charts |

## Getting Started

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn kagglehub
```

### 3. Open the Notebook

Open `notebook.ipynb` using Google Colab or Jupyter Notebook.

### 4. Run the Analysis

Execute the notebook cells in order to:

1. Download the California Housing dataset.
2. Inspect and clean the data.
3. Analyze missing values and capped house prices.
4. Generate statistical summaries.
5. Create visualizations.
6. Export the cleaned dataset.

## Learning Outcomes

Through this project, I practiced:

- Working with real-world datasets.
- Data inspection and preprocessing.
- Handling missing values and duplicate records.
- Identifying target value limitations.
- Exploratory Data Analysis.
- Geographical data visualization.
- Statistical analysis and correlation.
- Preparing datasets for machine learning.

## Author

**Muhammad Sameer Mustaqeem**

- GitHub: [sameermustaqeem878-source](https://github.com/sameermustaqeem878-source)
- LinkedIn: [Muhammad Sameer Mustaqeem](https://www.linkedin.com/in/m-sameer-mustaqeem-b1a436317/)
