<img src="thumbnail.png" alt="thumbnail" width="300"/>

# OSDF Cookbook

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

This Project Pythia Cookbook covers examples that demonstrate data access via the Open Science Data Federation. 
## Motivation

(Add a few sentences stating why this cookbook will be useful. What skills will you, "the chef", gain once you have reached the end of the cookbook?)
Info about the Open Science Data Federation : https://osg-htc.org/services/osdf.html. We will use the 
[PelicanFS](https://github.com/PelicanPlatform/pelicanfs?tab=readme-ov-file) package to access data.

## Authors

[Harsha Hampapura](https://github.com/hrhampapura), [Second Author](@second-author)

### Contributors

<a href="https://github.com/ProjectPythia/osdf-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/osdf-cookbook" />
</a>

## Structure

This cookbook is broken up into two main sections - "Foundations" and "Example Workflows."

### Section 1 ( Foundations)

The foundational content includes an introduction to the Open Science Data Federation, its data origins and [PelicanFS](https://github.com/PelicanPlatform/pelicanfs?tab=readme-ov-file), which is a file system interface (fsspec) for the [Pelican Platform](https://pelicanplatform.org)

### Section 2 ( Example workflows )

Example workflows include i) Accessing CESM2 LENS data from the AWS origin and the ii) NCAR origin iii) Accessing NOAA SONAR data from the AWS origin

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/ProjectPythia/osdf-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/osdf-cookbook.git
   ```

1. Move into the `osdf-cookbook` directory
   ```bash
   cd osdf-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate osdf-cookbook
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
