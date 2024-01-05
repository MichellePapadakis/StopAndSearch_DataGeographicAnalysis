# MY472_PSF
# Descriptive Analysis of Stops and Searches in London

## Repository Overview

- This repository contains an R Markdown (`.Rmd`) file dedicated to performing a Descriptive Analysis of Stops and Searches within London.
- It also contains the final output as (`.html`) file. With a short report of 754 words about the most relevant findinds.
- A `data` folder to replicate the interactive maps when running the code.


### Data Folder

The `data` folder is a key component of this repository, housing the Statistical GIS Boundary Files for London, which are sourced from the [London Datastore](https://data.london.gov.uk/dataset/statistical-gis-boundary-files-london).

### Analysis in R Markdown

The `.Rmd` file is designed to:

- Perform web scraping from sources like Wikipedia, the UK Police Data API, and the Office of National Statistics.
- Automatically load the downloaded information into the RStudio environment.
- Utilize relative file paths for downloading and loading data, negating the need for path modifications.

### Repository Structure

For seamless operation, it is essential to maintain the current folder structure. This approach ensures that the relative paths used in the R Markdown file function correctly.

---

**Note:** Keeping the folder structure intact is crucial for the effectiveness of the relative paths in the analysis.
