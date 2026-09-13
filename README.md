# Netflix Data Analysis

Exploratory data analysis of Netflix titles using a Jupyter notebook and a curated dataset.

## Project Overview

This repository analyzes Netflix catalog data with a focus on movie trends, including 1990s releases and genre patterns. The main analysis is contained in a single notebook and is designed for iterative exploration.

## Repository Structure

- `/home/runner/work/netflix-data-analysis/netflix-data-analysis/notebook.ipynb` — primary analysis notebook
- `/home/runner/work/netflix-data-analysis/netflix-data-analysis/netflix_data.csv` — source dataset used by the notebook
- `/home/runner/work/netflix-data-analysis/netflix-data-analysis/redpopcorn.jpg` — image asset displayed in the notebook

## Dataset

The dataset contains **4,812** Netflix titles with the following columns:

- `show_id`
- `type`
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `duration`
- `description`
- `genre`

## Requirements

- Python 3.9+
- Jupyter Notebook or JupyterLab
- Recommended Python packages:
  - `pandas`
  - `matplotlib`
  - `numpy`

## Getting Started

1. Clone the repository.
2. Navigate to the project directory:
   ```bash
   cd /home/runner/work/netflix-data-analysis/netflix-data-analysis
   ```
3. (Optional) Create and activate a virtual environment.
4. Install dependencies:
   ```bash
   pip install pandas matplotlib numpy jupyter
   ```
5. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
6. Open `notebook.ipynb` and run cells in order.

## Analysis Scope

Current notebook exploration includes:

- Reading and inspecting Netflix title metadata
- Filtering titles by release period and type
- Visual exploration of movie patterns

## Notes

- The notebook reads `netflix_data.csv` from the repository root.
- Keep large output artifacts out of version control (covered by `.gitignore`).

## Contributing

Contributions are welcome through pull requests that improve analysis quality, reproducibility, or documentation.
