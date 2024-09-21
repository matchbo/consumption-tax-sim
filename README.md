# Consumption Tax Simulation

This project simulates the effects of a consumption tax system with provenance-based choices.

## Setup

This project uses Rye for dependency management.

1. Ensure you have Rye installed.
2. Clone this repository.
3. Navigate to the project directory.
4. Run `rye sync` to install dependencies.

## Running the Simulation

1. Activate the Rye environment: `rye shell`
2. Run the simulation: `python src/consumption_tax_sim/run_simulation.py`

## Analyzing Results

1. Start Jupyter Notebook: `jupyter notebook`
2. Open `notebooks/analysis.ipynb`
3. Run the cells to visualize the results

## Project Structure

- `src/consumption_tax_sim/`: Contains the main simulation code
- `data/`: Stores simulation results
- `notebooks/`: Contains Jupyter notebooks for analysis
