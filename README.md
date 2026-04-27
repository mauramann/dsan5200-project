# DSAN 5200 Final Project

This project looks at various data sets from the U.S. Department of Agriculture's Economic Research Service database and focuses on analyzing the adoption of crop genetic engineering through various data visualizations. 

---

## Project Overview

* data-cleaning: folder holding juypter notebook script used to clean the raw data.
* data-viz: folder holding juypter notebook script used to create all plots.
* tables: folder holding matplotlib tables later embedded into the infographic in data-viz.ipynb.
* website: folder holding all content to create the quarto website.

---

## How It Works

When the website folder is rendered, a new _dsan5200site folder is created, which is then pushed to my individual Georgetown domain for hosting.

The website folder includes:

* _dsan5200site: rendered quarto markdown website.
* images: non-coded images embedded in the website.
* plots: coded plots embededd in the website.
* _quarto.yml: website structure.
* appendix.qmd: the 'Technical Appendix' page describing data cleaning and wrangling techniques performed.
* index.qmd: the 'Home' page of the website with the main content analysis.
* llmlog.qmd: the 'LLM Log' page of the website with all llm use cases listed.
* sources.qmd: the 'Sources' page of the website with data sources listed.
* references.bib: a list of all academic sources referenced in the 'Home' page.
* styles.css: all code used for the UI design of the website.

---

## Package Requirements

* altair 6.0.0+
* vega-datasets 0.9.0+
* plotly 6.5.0+
* matplotlib 3.10.8+

## Data

The data sets used in this analysis can be found at the websites listed below. They are were included in the data/ folder that was excluded in the .gitignore.

* Genetically Engineered Crop Data (Years, Crops, Percentages, Attributes): https://www.ers.usda.gov/data-products/adoption-of-genetically-engineered-crops-in-the-united-states 
* U.S. Farm Income Statistics: https://ers.usda.gov/data-products/farm-income-and-wealth-statistics/data-files-us-and-state-level-farm-income-and-wealth-statistics
* U.S. Research & Development Spending: https://www.ers.usda.gov/data-products/agricultural-and-food-research-and-development-expenditures-in-the-united-states

## Author
Maura Mann