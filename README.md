# Basic Graph Plotting with Matplotlib

This repository contains a Jupyter Notebook demonstrating how to create a simple graph using Matplotlib in Python. The notebook plots a linear function (y = 2x) and a quadratic function (y = x²) on the same graph, with customized styling and annotations.

## Features
- Plots a linear function (`y = 2x`) using blue triangles with a dashed line.
- Plots a quadratic function (`y = x²`) with a solid red line for the first part and a dashed red line for the remainder.
- Customizes the graph with a title, axis labels, and a legend.
- Sets specific tick marks on the x-axis.
- Saves the graph as a high-resolution PNG file (`mygraph.png`).
- Displays the plot in the notebook.

## Prerequisites
To run the notebook, you need the following Python libraries installed:
- `matplotlib`
- `numpy`
- `pandas` (included but not used in this example)

You can install them using pip:
```bash
pip install matplotlib numpy pandas
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/basic-graph-plotting.git
   ```
2. Navigate to the repository folder:
   ```bash
   cd basic-graph-plotting
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Untitled1.ipynb
   ```
4. Run the cells in the notebook to generate and display the graph.
5. The graph will be saved as `mygraph.png` in the same directory.

## Example Output
The notebook generates a graph with:
- A blue dashed line with triangle markers for `y = 2x`.
- A red solid line for `y = x²` up to x = 2.5, transitioning to a red dashed line beyond.
- Labeled axes, a title ("Basic graph"), and a legend.
- A high-resolution PNG file (`mygraph.png`) saved locally.

## File Structure
- `Untitled1.ipynb`: The main Jupyter Notebook containing the plotting code.
- `mygraph.png`: The output graph (generated after running the notebook).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
