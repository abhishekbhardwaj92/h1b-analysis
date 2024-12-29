# H1B-2024 Single Registration Data Analysis

## Overview
This project analyzes H1B-2024 single registration data to uncover trends, insights, and patterns regarding H1B visa applicants and employers. The analysis focuses on key aspects such as employers, countries of origin, job roles, wages, and worksite locations.

## Features
- Data cleaning and preprocessing for robust analysis.
- Exploratory data analysis (EDA) with insights into:
  - Top employers and their sponsorship trends.
  - Most common job roles and their respective wage distributions.
  - Geographic distribution of applicants and worksites.
- Interactive visualizations using Matplotlib and Seaborn.

## Dataset
- **Source**: (https://github.com/BloombergGraphics/2024-h1b-immigration-data)
- **Columns Used**: 
  - `employer_name`
  - `country_of_birth`
  - `JOB_TITLE`
  - `WAGE_AMT`
  - `WORKSITE_STATE`

> **Note**: Ensure the dataset is anonymized and follows data privacy regulations before usage.

## Requirements
To run this project, install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

## File Structure
- `h1b_analysis.ipynb`: Jupyter Notebook containing the complete analysis.
- `README.md`: Project documentation.
- `h1b_2024_data.csv`: Dataset for the analysis (not included in the repository).

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd h1b-analysis
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook h1b_analysis.ipynb
   ```
4. Run the cells to load and analyze the data.

## Analysis Highlights
- **Top Employers**:
  - Identified the most active sponsors of H1B registrations.
  - Visualized employer trends with bar charts.

- **Country of Birth**:
  - Highlighted top countries of origin for applicants.
  - Provided insights into demographic distributions.

- **Job Titles and Wages**:
  - Analyzed popular job roles and their wage statistics.
  - Plotted wage distributions for various roles.

- **Worksite Locations**:
  - Mapped the top U.S. states hosting H1B worksites.

## Visualization Examples
- Bar charts for top employers, job titles, and worksite states.
- Histogram for wage distribution.
- Country-wise distribution for applicants.

## Future Enhancements
- Include time-series analysis for multi-year trends.
- Incorporate advanced machine learning models for prediction.
- Expand visualizations using Plotly or Tableau.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
-  [Data Source]: (https://github.com/BloombergGraphics/2024-h1b-immigration-data)
  
## Contact
For questions or contributions, reach out via comment
