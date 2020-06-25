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

To run the notebooks, you need to install [Anaconda](https://www.anaconda.com/).

You can clone or download the repository.

To clone it using `git`:
```
git clone https://github.com/aguspesce/online_seminar.git
```

Or you can download it as a `zip` through [this link]
(https://github.com/aguspesce/online_seminar/archive/master.zip)

Then, create an environment with all the dependencies through the conda package manager:
```
conda env create -f environment.yml
```

Then, activate the environment:
```
conda activate online-seminar
```

Finally you can run an instance of `Jupyter Notebook` with:
```
jupyter-notebook
```
or
```
jupyter-lab
```
This will open a window in our browser, through which you can open and run the
notebooks.

## License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International

License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

