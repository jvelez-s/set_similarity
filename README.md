# Set Similarity

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting.
    │
    └── environment.yml   <- The environment file for reproducting the analysis environment.

--------

## Guide of installation
 
 1. Clone the repository.
 2. Install [conda](https://docs.conda.io/projects/conda/en/latest/index.html).
 3. Install project dependencies: `conda env create -f environment.yml`.
 4. Activate conda environment: `conda activate set_similarity`.
 
## Working
 1. The work environment includes jupyter so you can work typing `jupyter-lab` on terminal.
  However feel free to use the development environment of your liking.
 2. Read **notebooks/0.0-jvs-introduction.ipynb** to understand the way of working.
 3. Start working.
 4. If you install new dependencies or update the versions, you must reflect the changes in the environment.
