# Seagrass Turbidity Cookbook

<img src="thumbnails/thumbnail.png" alt="thumbnail" width="300"/>

[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ssullivan9661/seagrass-turbidity-cookbook/main?labpath=notebooks)


This cookbook covers the spatiotemporal analysis project of coastal seagrass in Florida Bay, working with Sentinel-2 satellite imagery and water quality data in Python. 

## Motivation

The purpose of this cookbook is to document a reproducible workflow for integrating satellite imagery with environmental data to analyze coastal ecosystem health. Looping over large raster data files to convert file types, save to `.nc`, process by clipping and masking, and calculating spectral indices with modules such as Xarray and Rasterio. Process water quality data with Pandas, NumPy, Matplotlib, and other python functions and modules to perform a comparison analysis of spatiotemporal data and environmental data. Ultimately, creating a workflow that can be applied to other environmental applications for spatial-temporal comparison analysis of raster and numeric data.



## Authors

[Sara Sullivan](https://github.com/ssullivan9661), [Daniel Smith](https://github.com/ianraymondsmith), and [Omar Alazmi](https://github.com/engomarm03-commits)


## Structure

(State one or more sections that will comprise the notebook. E.g., _This cookbook is broken up into two main sections - "Foundations" and "Example Workflows."_ Then, describe each section below.)

### Section 1 ( Replace with the title of this section, e.g. "Foundations" )

(Add content for this section, e.g., "The foundational content includes ... ")

### Section 2 ( Replace with the title of this section, e.g. "Example workflows" )

(Add content for this section, e.g., "Example workflows include ... ")

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
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter).

Note, not all Cookbook chapters are executable. If you do not see
the rocket ship icon, such as on this page, you are not viewing an
executable book chapter.


### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/cookbook-example` repository:

   ```bash
    git clone https://github.com/ProjectPythia/cookbook-example.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd cookbook-example
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-example
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
