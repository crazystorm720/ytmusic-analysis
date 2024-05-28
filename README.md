# YouTube Music Metrics

This project analyzes and visualizes your YouTube Music listening history data using the `ytmusicapi` library and Python.

## Prerequisites

- Python 3.9 or higher
- Conda package manager

## Getting Started

1. Clone the project repository:

   ```bash
   git clone https://github.com/your-username/youtube-music-metrics.git
   cd youtube-music-metrics
   ```

2. Create and activate the conda environment:

   ```bash
   conda env create -f environment.yml
   conda activate youtube-music-metrics
   ```

3. Install the additional Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the `notebooks/listening_history_analysis.ipynb` notebook and follow the instructions to authenticate with the YouTube Music API and perform the analysis.

## Project Structure

- `docs/`: Contains the mkdocs documentation files
  - `index.md`: The main page of the documentation
  - `visuals.md`: Showcases the visualizations created during the analysis
- `notebooks/`: Contains the Jupyter Notebook files
  - `listening_history_analysis.ipynb`: The main notebook for analyzing the listening history data
- `.gitignore`: Specifies files and directories to be ignored by Git
- `environment.yml`: Defines the conda environment and dependencies
- `mkdocs.yml`: Configuration file for mkdocs
- `README.md`: Provides an overview of the project
- `requirements.txt`: Lists the Python packages required for the project

## Lifecycle Commands

- Build the mkdocs site:

  ```bash
  mkdocs build
  ```

- Serve the mkdocs site locally:

  ```bash
  mkdocs serve
  ```

- Deploy the mkdocs site to GitHub Pages:

  ```bash
  mkdocs gh-deploy
  ```

## Deactivating the Environment

To deactivate the conda environment and clean up the resources:

1. Deactivate the conda environment:

   ```bash
   conda deactivate
   ```

2. Remove the conda environment (optional):

   ```bash
   conda env remove -n youtube-music-metrics
   ```

3. Close any running Jupyter Notebook instances.

## Contributing

If you would like to contribute to this project, please follow the guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the [MIT License](LICENSE).
