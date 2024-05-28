# YouTube Music Metrics

Welcome to the YouTube Music Metrics project! This project aims to analyze and visualize your YouTube Music listening history data using the `ytmusicapi` library and Python.

## Project Overview

The main goals of this project are:

- Retrieve your YouTube Music listening history data using the `ytmusicapi` library
- Analyze your listening patterns over time, such as hourly, daily, or weekly trends
- Identify your most played songs, artists, or genres based on the listening history
- Visualize your listening activity using line graphs or heatmaps to showcase temporal patterns
- Document the findings, insights, and visualizations using mkdocs

## Getting Started

To get started with this project, follow these steps:

1. Clone the project repository from GitHub
2. Create and activate the conda environment using the provided `environment.yml` file
3. Obtain YouTube Music API credentials and add them to the `auth.json` file
4. Launch Jupyter Notebook and open the `listening_history_analysis.ipynb` notebook
5. Run the code cells in the notebook to perform the analysis

## Project Structure

The project structure is as follows:

- `auth.json`: Contains the YouTube Music API authentication credentials (not tracked by Git)
- `docs/`: Contains the mkdocs documentation files
  - `images/`: Directory to store visualization images
  - `index.md`: The main page of the documentation (this file)
  - `visuals.md`: Showcases the visualizations created during the analysis
- `notebooks/`: Contains the Jupyter Notebook files
  - `listening_history_analysis.ipynb`: The main notebook for analyzing the listening history data
- `.gitignore`: Specifies files and directories to be ignored by Git
- `environment.yml`: Defines the conda environment and dependencies
- `mkdocs.yml`: Configuration file for mkdocs
- `README.md`: Provides an overview of the project
- `requirements.txt`: Lists the Python packages required for the project

## Visualizations

Check out the [Visualizations](visuals.md) page to see the interesting insights and patterns discovered from your YouTube Music listening history data.
