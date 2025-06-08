# Data Analysis and Visualization Project

This repository contains a Jupyter Notebook (`Untitled1.ipynb`) that demonstrates data visualization and analysis using Python. The notebook includes:

1. **Graph Plotting**: A basic example of plotting a linear function (`y = 2x`) and a quadratic function (`y = x²`) using Matplotlib.
2. **Gas Prices Analysis**: Exploratory data analysis of a gas prices dataset to uncover trends and insights.
3. **FIFA Dataset Analysis**: Analysis of a FIFA player dataset to explore player attributes and statistics.

## Features

### Graph Plotting
- Plots a linear function (`y = 2x`) using blue triangles with a dashed line.
- Plots a quadratic function (`y = x²`) with a solid red line up to `x = 2.5` and a dashed red line beyond.
- Customizes the graph with a title ("Basic graph"), axis labels, a legend, and specific x-axis tick marks.
- Saves the graph as a high-resolution PNG file (`mygraph.png`).

### Gas Prices Analysis
- Loads and cleans a dataset containing historical gas prices.
- Performs exploratory data analysis (EDA) to identify trends, such as average prices over time or by region.
- Visualizes findings using plots (e.g., line charts for price trends, bar charts for regional comparisons).
- Calculates summary statistics (e.g., mean, median, standard deviation) for gas prices.

### FIFA Dataset Analysis
- Loads a FIFA player dataset containing attributes like player ratings, positions, and nationalities.
- Conducts EDA to explore relationships between attributes (e.g., overall rating vs. age, nationality distribution).
- Creates visualizations such as histograms, scatter plots, and bar charts to illustrate player statistics.
- Identifies top players or trends in player attributes across different years or leagues.

## Prerequisites
To run the notebook, you need the following Python libraries:
- `matplotlib` (for plotting)
- `numpy` (for numerical operations)
- `pandas` (for data manipulation and analysis)
- `seaborn` (optional, for enhanced visualizations in data analysis)

Install the required libraries using pip:
```bash
pip install matplotlib numpy pandas seaborn
```

You also need Jupyter Notebook or JupyterLab to run the `.ipynb` file:
```bash
pip install jupyter
```

### Datasets
- **Gas Prices Dataset**: Assumed to be a CSV file (e.g., `gas_prices.csv`) with columns like date, price, and region. Place this file in the repository's root directory.
- **FIFA Dataset**: Assumed to be a CSV file (e.g., `fifa_players.csv`) with columns like player name, overall rating, age, nationality, and club. Place this file in the repository's root directory.

*Note*: The datasets are not included in this repository. You must provide or source them separately (e.g., from Kaggle or another data provider).

## Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/data-analysis-visualization.git
   ```
2. **Navigate to the repository folder**:
   ```bash
   cd data-analysis-visualization
   ```
3. **Place the datasets**:
   - Copy `gas_prices.csv` and `fifa_players.csv` (or your dataset files) into the repository's root directory.
4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook Untitled1.ipynb
   ```
5. **Run the notebook**:
   - Execute the cells in order to:
     - Generate and save the basic graph (`mygraph.png`).
     - Perform and visualize gas prices analysis.
     - Perform and visualize FIFA dataset analysis.
   - Ensure the dataset files are in the correct path as referenced in the notebook.

## Example Outputs
- **Graph Plotting**:
  - A graph with a blue dashed line with triangle markers for `y = 2x` and a red line (solid then dashed) for `y = x²`.
  - Saved as `mygraph.png` in the repository's root directory.
- **Gas Prices Analysis**:
  - Line plots showing gas price trends over time.
  - Bar charts comparing average prices by region.
  - Summary statistics printed in the notebook (e.g., mean price, max price).
- **FIFA Dataset Analysis**:
  - Histograms of player ratings or ages.
  - Scatter plots of overall rating vs. potential or age.
  - Bar charts of top nationalities or clubs by player count.

## File Structure
```
data-analysis-visualization/
├── Untitled1.ipynb         # Jupyter Notebook with plotting and data analysis
├── mygraph.png            # Output graph from the plotting section
├── gas_prices.csv         # Gas prices dataset (not included, user-provided)
├── fifa_players.csv       # FIFA dataset (not included, user-provided)
├── README.md              # This README file
└── LICENSE                # License file (optional)
```

## Notebook Structure
The `Untitled1.ipynb` notebook is organized as follows:
1. **Imports**: Loads required libraries (`matplotlib`, `numpy`, `pandas`).
2. **Graph Plotting**:
   - Defines data for linear and quadratic functions.
   - Creates and customizes the plot.
   - Saves and displays the graph.
3. **Gas Prices Analysis**:
   - Loads `gas_prices.csv`.
   - Cleans and preprocesses the data.
   - Performs EDA and generates visualizations.
4. **FIFA Dataset Analysis**:
   - Loads `fifa_players.csv`.
   - Cleans and preprocesses the data.
   - Performs EDA and generates visualizations.

## Notes
- Ensure the dataset files (`gas_prices.csv` and `fifa_players.csv`) match the expected column structure used in the notebook. Modify the notebook's data loading cells if your dataset has different column names.
- The plotting section has a high-resolution output (300 DPI) for `mygraph.png`, suitable for presentations or reports.
- For large datasets, consider optimizing the analysis code (e.g., using vectorized operations in `pandas`) to improve performance.
- The notebook assumes basic familiarity with Python and Jupyter Notebooks.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

Please open an issue to discuss bugs or feature requests before submitting changes.

## Acknowledgments
- The plotting section is inspired by Matplotlib's documentation and tutorials.
- Gas prices and FIFA datasets are assumed to be sourced from public data platforms like Kaggle.
- Thanks to the Python community for maintaining `matplotlib`, `numpy`, `pandas`, and `seaborn`.
