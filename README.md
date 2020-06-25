# Online seminar of the laboratorio de tectonofisica from IAG-USP

### Title: How to manage multi-dimensional arrays?

__Summary__

Xarray is an open source project and Python package that makes working with labelled
multi-dimensional arrays simple, efficient and with fewer errors.
Xarray is inspired by and borrows heavily from pandas.
It is particularly tailored to work with netCDF files and integrates tightly with Dask
for parallel computing.

On this opportunity, I want to convey to you why I consider Xarray a very powerful tool
and show you some functionalities that I frequently use on my research.
I will also show some examples on how I use Xarray for manage, store and visualize data
produced by the geodynamical modelling software Mandyoc, developed by Victor Sacek
(USP).

## How to run the notebooks?

For run the notebooks, it is necessary to install a Python distribution.
One of the best options is to install [Anaconda](https://www.anaconda.com/).

### Using Anaconda:

Yo can clone or download the repository.

To clone it using `git`:
```
git clone https://github.com/aguspesce/online_seminar.git
```

Or you can download it as a `zip` through [this link]

Then, install all the dependencies through the conda package manager:
```
conda env create -f environment.yml
```

And then activate the environment:
```
conda activate online-seminar
```

Finally, run `jupyter notebook` or `jupyter-lab`.

