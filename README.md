# How to manage multi-dimensional arrays?

by [Agustina Pesce](https://github.com/aguspesce)

> Online seminar of the laboratorio de tectonofisica from IAG-USP

## Summary

[Xarray](https://xarray.pydata.org/en/stable/) is an open source project and
Python package that makes working with labelled multi-dimensional arrays
simple, efficient and with fewer errors. Xarray is inspired by and borrows
heavily from [pandas](https://pandas.pydata.org/). It is particularly tailored
to work with netCDF files and integrates tightly with [Dask](https://dask.org/)
for parallel computing.

On this opportunity, I want to convey to you why I consider Xarray a very
powerful tool and show you some functionalities that I frequently use on my
research. I will also show some examples on how I use Xarray for manage, store
and visualize data produced by the geodynamical modelling software
[Mandyoc](https://bitbucket.org/victorsacek/mandyoc/src/master/), developed by
Victor Sacek (USP).

## How to run the notebooks?

To run the notebooks, you need to install [Anaconda](https://www.anaconda.com/).

Download the notebooks by cloning this repository through `git`:
```
git clone https://github.com/aguspesce/online_seminar
```

Alternatively, you can download it as a `zip` through
[this link](https://github.com/aguspesce/online_seminar/archive/master.zip)

Then, create a conda environment that includes all the needed dependencies
through the `conda` package manager:
```
conda env create -f environment.yml
```

And activate the environment:
```
conda activate online-seminar
```

Finally you can run an instance of Jupyter Notebook with:
```
jupyter-notebook
```

This will open a new tab in your browser, through which you can open and run the
notebooks.

## License

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
