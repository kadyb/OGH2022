This repository contains materials for the "**Benchmarking R and Python for spatial data processing**" workshop on [OpenGeoHub Summer School 2022](https://opengeohub.org/summer-school/siegburg-2022/).

## Introduction

R and Python are the two most popular scripting languages used to process spatial data.
Both are great alternatives to desktop GIS software allowing for reproducible research.
In this workshop, we will examine the differences between the most popular packages for spatial data processing and test their performance.

If you are a beginner in spatial data science, you will find interesting books here:
 - [Spatial Data Science with applications in R](https://www.r-spatial.org/book)
 - [Spatial Data Science with R and “terra”](https://rspatial.org/terra/)
 - [Geocomputation with R](https://geocompr.robinlovelace.net/)
 - [Introduction to Python for Geographic Data Analysis](https://pythongis.org/)
 - [Geocomputation with Python](https://geocompr.github.io/py/)

If you would like to see extended versions of the benchmarks, here are the repositories for the [vector](https://github.com/kadyb/vector-benchmark) and [raster](https://github.com/kadyb/raster-benchmark) packages.

## Requirements

**Hardware:**

Your hardware should have a minimum of 8 GB RAM.
In case you do not have access to such a configuration, there is a small raster file in the "data" folder, which can be used for this workshop.
The operating system is arbitrary, but make sure all packages are working properly.

**Software:**

 - **R**: RStudio, sf, stars, terra, bench, microbenchmark
 - **Python**: Jupyter Notebook, geopandas*, rasterio

*geopandas is much faster when pygeos is installed (reading and writing is also faster with pyogrio)

If possible, you should use the latest software versions.

## Materials

 1. [R](https://kadyb.github.io/OGH2022/R.html)
 2. [Python](https://kadyb.github.io/OGH2022/Python.html)

To start Jupyter Notebook, type in the terminal (or Anaconda Prompt):

```
jupyter notebook
```

Then it will launch the environment in your web browser.

## Contact
 
If you have any questions or need help, please let me know at [Mattermost](https://mattermost.opengeohub.org) or email me (krzysztof.dyba@amu.edu.pl).
