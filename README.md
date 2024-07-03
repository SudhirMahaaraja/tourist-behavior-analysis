# Tourist Behavior Analysis

This repository contains Jupyter notebooks for analyzing tourist behavior in India and Turkey. Each notebook performs exploratory data analysis (EDA) on the respective tourism data to uncover patterns and insights.

## Notebooks

1. **tourism_INDIA.ipynb**
   - Performs exploratory data analysis on tourism data for India.
   - Generates correlation matrices and scatter plots to identify relationships and distributions in the data.

2. **tourism_Turkey.ipynb**
   - Analyzes tourism data for Turkey.
   - Processes and visualizes tourist numbers from various countries, focusing on yearly and monthly trends.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries: `matplotlib`, `numpy`, `pandas`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tourist-behavior-analysis.git
   ```
2. Change to the repository directory:
   ```bash
   cd tourist-behavior-analysis
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open the desired notebook (e.g., `tourism_INDIA.ipynb` or `tourism_Turkey.ipynb`) in Jupyter.

### tourism_INDIA.ipynb

#### Overview

- **Libraries Used**:
  - `matplotlib` for plotting
  - `numpy` for linear algebra
  - `os` for accessing directory structure
  - `pandas` for data processing and CSV file I/O

- **Functions**:
  - `plotCorrelationMatrix(df, graphWidth)`: Plots the correlation matrix for the dataframe.
  - `plotScatterMatrix(df, plotSize, textSize)`: Plots scatter and density plots for numerical columns in the dataframe.

- **Steps**:
  1. Import required libraries.
  2. Define functions for plotting.
  3. Load the dataset (`tourism.csv`).
  4. Plot the correlation matrix and scatter plots.

### tourism_Turkey.ipynb

#### Overview

- **Libraries Used**:
  - `pandas` for data processing and CSV file I/O
  - `matplotlib` for plotting

- **Steps**:
  1. Import required libraries.
  2. Load the dataset (`tourist_numbers_Turkey.csv`).
  3. Set appropriate column names and process the data.
  4. Perform EDA to analyze tourist numbers by continent and country.
  5. Plot yearly and monthly trends.

## Data

- The datasets used in these analyses (`tourism.csv` for India and `tourist_numbers_Turkey.csv` for Turkey) should be placed in the same directory as the notebooks.

## Contributing

Feel free to contribute to this repository by submitting issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
