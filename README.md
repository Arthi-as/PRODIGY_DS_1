# Data Distribution Visualization

## Overview
This project analyzes and visualizes global population data using Python. It explores world population statistics from the World Bank API dataset, performing comprehensive data exploration and visualization.

## Project Description
The **Data_distribution_visualization.ipynb** notebook provides:
- Data loading and exploration of world population statistics
- Data cleaning and preprocessing
- Statistical analysis of population data
- Visualization of population distributions across countries
- Analysis of top countries by population metrics

## Technologies Used
- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization

## Data Source
- Source: World Bank API
- Dataset: Population, total (SP.POP.TOTL)
- File: API_SP.POP.TOTL_DS2_en_csv_v2_40826.xlsx

## Key Features
- Load and explore population data from Excel
- Data quality assessment (duplicates, missing values)
- Statistical summary of population metrics
- Identification of top 10 countries by population
- Visualization of distribution patterns
- Detailed exploratory data analysis (EDA)

## Project Structure
```
task1/
├── Data_distribution_visualization.ipynb   # Main analysis notebook
├── API_SP.POP.TOTL_DS2_en_csv_v2_40826.xlsx # Population dataset
└── README.md                                # This file
```

## Usage
1. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```

2. Open the Jupyter notebook:
   ```bash
   jupyter notebook Data_distribution_visualization.ipynb
   ```

3. Run cells sequentially to:
   - Load and explore the dataset
   - Perform data cleaning
   - Generate visualizations
   - Analyze population trends

## Key Sections
- **Data Loading**: Read population data from Excel file
- **Exploratory Data Analysis**: View dataset structure, statistics, and quality
- **Data Cleaning**: Handle missing values and duplicates
- **Top Countries Analysis**: Identify and analyze top 10 countries by population
- **Visualization**: Create insightful charts and graphs

## Notes
- Ensure the Excel file path is correctly set in the notebook
- The dataset contains population data for multiple countries across different years
- Visualizations help identify trends and distribution patterns in global population

## Author
Created as part of data analysis and visualization project

## License
Dataset sourced from World Bank Open Data
