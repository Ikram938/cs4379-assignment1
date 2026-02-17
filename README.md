# Netflix Titles Analysis

**Course:** CS4379  
**Student:** Ikram Yahya  

## Repository Overview

This repository contains my submission for Assignment 1.  

- **Part A:** Practice core Git/GitHub workflows including branching, commits, pull requests, and repository organization.  
- **Part B:** A reproducible data analysis of the Netflix titles dataset using a Jupyter Notebook, including data cleaning, analysis, and visualization.

---

## Part B Overview

This project analyzes the Netflix titles dataset to explore trends in the catalog over time. The main focus is on:

- How many titles are added to Netflix each year.
- Distribution of release years of the titles available on Netflix.

## Files in this Repository

- `notebooks/analysis.ipynb` — Original Jupyter notebook containing the analysis.  
- `notebooks/analysis.html` — HTML export of the notebook (for viewing without Jupyter).  
- `data/netflix_titles.csv` — Dataset used in the analysis.  
- `README.md` — This file.

## How to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/Ikram938/cs4379-assignment1.git
2. Make sure you have Python installed (Python 3.8+ recommended).

3. Install the required packages:
   pip install pandas numpy matplotlib seaborn
4. Open the notebook:
   jupyter notebook notebooks/analysis.ipynb
5. Run all the cells to reproduce the analysis and plots.

Results / Findings

The number of Netflix titles added per year has increased significantly since 2016, peaking around 2019.

The distribution of release years shows that most titles available on Netflix were released in recent years, though older movies are also present.

Visualizations include a histogram of release years and a line plot showing titles added per year.

Notes

Missing or null values were handled appropriately during the analysis.

Both the .ipynb and .html files are provided for convenience

---

## Git Workflow (Part A Summary)

- Repository initialized locally and pushed to GitHub.
- Created a branch named `analysis-notebook`.
- Added notebook in `notebooks/` directory.
- Made multiple logical commits with descriptive messages.
- Opened and merged a Pull Request into `main`.
- Added a `.gitignore` file for Python/Jupyter projects.

---

