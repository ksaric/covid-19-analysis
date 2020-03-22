# COVID-19 analysis

The notebook accompanying the blog post https://exact-byte.com/hr/covid-19-vizualizacija/ which is in Croatian (for now, I can translate it).

This notebook fetches data from the external repo https://github.com/CSSEGISandData/COVID-19 which it then uses for visualizations.
The nice thing about the repo is that it gets updated and every day (or minute if you are paranoid) you can check out the progress and re-run all the visualizations to see the status.

## How to install/run this?

Well, you should follow the intructions.

The instructions are:
1. Download Anacodnda from https://www.anaconda.com/distribution/, the Python 3.7 distribution
2. Create the environment for this notebook:
```
conda create -n covid-analysis python=3.7
conda activate covid-analysis

conda install -c conda-forge jupyterlab

conda install numpy pandas
conda install plotly seaborn
```
3. Update the datasource with `git submodule update --init --recursive` or `git submodule update --recursive --remote`
4. Run with `jupyter notebook`



