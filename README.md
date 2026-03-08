# LEGO Data Manipulation Project

## Overview
This project analyzes LEGO set, theme, minifig, part, and color data using pandas in a Jupyter notebook.

Primary notebook:
- `lego.ipynb`

The notebook focuses on data manipulation workflows such as filtering, grouping, sorting, joining, and building helper functions for reusable queries.

## Tech Stack
- Python 3
- Jupyter Notebook
- pandas
- numpy

## Dataset Files
Place these CSV files in the same directory as `lego.ipynb`:
- `sets.csv`
- `themes.csv`
- `inventories.csv`
- `inventory_sets.csv`
- `inventory_minifigs.csv`
- `minifigs.csv`
- `inventory_parts.csv`
- `parts.csv`
- `part_categories.csv`
- `colors.csv`
- `part_relationships.csv`
- `elements.csv`

## Key Analysis Areas
The notebook includes tasks and functions covering:
- Basic set-level metrics (counts, averages, medians, maximums)
- Selecting sets by ID, year, and number of parts
- Theme-level analysis across years and names
- Minifig lookups by set and theme
- Part and color exploration (including transparent colors)

## Core Helper Functions
Implemented functions include:
- `data_count`
- `select_set_row`
- `select_set_numparts`
- `select_set_year`
- `theme_by_year`
- `theme_by_name`
- `theme_by_setnum`
- `get_minifigs`
- `minifigs_from_themes`
- `sets_from_minifig`
- `set_parts`
- `get_part_colors`

## How to Run
1. Open a terminal in this project folder.
2. Launch Jupyter:
   - `jupyter notebook`
3. Open `lego.ipynb`.
4. Run all cells from top to bottom to ensure all DataFrames and helper functions are initialized.

## Notes
- Some outputs depend on the exact CSV contents and row-level matches, so keep original files unchanged for reproducible results.
