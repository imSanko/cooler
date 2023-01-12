# Cooler

<a href="https://open2c.github.io/cooler"><img width="25%" src="https://github.com/open2c/cooler/raw/master/docs/cooler_logo.png" alt="Cooler"></a>

<table>
    <tr>
        <td>Latest Release</td>
        <td>
            <a href="https://pypi.org/project/cooler/">
                <img src="https://badge.fury.io/py/cooler.svg" alt="latest release pypi" />
            </a>
            <a href="https://bioconda.github.io/recipes/cooler/README.html">
                <img src="https://anaconda.org/bioconda/cooler/badges/version.svg" alt="latest release bioconda">
            </a>
        </td>
    </tr>
    <tr>
        <td>License</td>
        <td>
            <a href="https://github.com/open2c/cooler/blob/master/LICENSE">
                <img src="https://img.shields.io/pypi/l/cooler.svg" alt="license">
            </a>
        </td>
    </tr>
    <tr>
        <td>Build Status</td>
        <td>
            <a href="https://github.com/open2c/cooler/blob/main/.github/workflows/lint-test-cov.yml">
                <img src="https://github.com/open2c/cooler/actions/workflows/lint-test-cov.yml/badge.svg" alt="build status">
            </a>
        </td>
    </tr>
    <tr>
        <td>Docs Status</td>
        <td>
            <a href="http://cooler.readthedocs.org/en/latest/">
                <img src="https://readthedocs.org/projects/cooler/badge/?version=latest">
            </a>
        </td>
    </tr>
    <tr>
        <td>Coverage</td>
        <td>
            <a href="https://codecov.io/gh/open2c/cooler">
                <img src="https://codecov.io/gh/open2c/cooler/branch/master/graph/badge.svg" alt="coverage">
            </a>
        </td>
    </tr>
    <tr>
        <td>Downloads</td>
        <td>
            <a href="https://pypi.org/project/cooler">
                <img src="https://static.pepy.tech/personalized-badge/cooler?period=total&units=international_system&left_color=grey&right_color=blue&left_text=PyPI%20downloads" alt="pypi downloads">
            </a>
            <a href="http://bioconda.github.io/recipes/cooler/README.html">
                <img src="https://img.shields.io/conda/dn/bioconda/cooler.svg?style=flat&label=Bioconda downloads" alt="bioconda downloads">
            </a>
        </td>
    </tr>
    <tr>
        <td>Community</td>
        <td>
            <a href="https://bit.ly/open2c-slack">
                <img src="https://img.shields.io/badge/chat-slack-%233F0F3F?logo=slack" alt="slack">
            </a>
        </td>
    </tr>
    <tr>
        <td>Zenodo</td>
        <td>
            <a href="https://zenodo.org/badge/latestdoi/49553222">
                <img src="https://zenodo.org/badge/49553222.svg" alt="zenodo doi">
            </a>
        </td>
    </tr>
</table>

## A cool place to store your Hi-C

Cooler is a support library for a **sparse, compressed, binary** persistent storage [format](http://cooler.readthedocs.io/en/latest/schema.html), also called cooler, used to store genomic interaction data, such as Hi-C contact matrices.

The cooler file format is an implementation of a genomic matrix data model using [HDF5](https://en.wikipedia.org/wiki/Hierarchical_Data_Format) as the container format. The `cooler` package includes a suite of [command line tools](http://cooler.readthedocs.io/en/latest/cli.html) and a [Python API](http://cooler.readthedocs.io/en/latest/api.html) to facilitate creating, querying and manipulating cooler files.

To get started:

- [Install](#Installation) cooler
- Read the [documentation](http://cooler.readthedocs.org/en/latest/) and see the Jupyter Notebook [walkthrough](https://github.com/open2c/cooler-binder).
- _cool_ files from published Hi-C data sets are available at `ftp://cooler.csail.mit.edu/coolers`.
- Many more multires (_mcool_) files are available on the [4DN data portal](https://data.4dnucleome.org/visualization/index).

### Installation

Install from PyPI using pip.
```sh
$ pip install cooler
```

If you are using `conda`, you can alternatively install `cooler` from the [bioconda](https://bioconda.github.io/index.html) channel.
```sh
$ conda install -c conda-forge -c bioconda cooler
```

Requirements:

- Python 3.6+
- libhdf5 and Python packages `numpy`, `scipy`, `pandas`, `h5py`. We highly recommend using the `conda` package manager to install scientific packages like these. To get it, you can either install the full [Anaconda](https://www.continuum.io/downloads) Python distribution or just the standalone [conda](http://conda.pydata.org/miniconda.html) package manager.

See the [docs](http://cooler.readthedocs.org/en/latest/) for more information.

Note: Python 2.7 support has ceased as of cooler 0.9.


### Contributing

Interested in contributing to cooler? That's great! To get started, check out the [contributing guide](https://github.com/open2c/cooler/blob/master/CONTRIBUTING.md).


### Citing

Abdennur, N., and Mirny, L. (2019). Cooler: scalable storage for Hi-C data and other genomically labeled arrays. _Bioinformatics_. doi: [10.1093/bioinformatics/btz540](https://doi.org/10.1093/bioinformatics/btz540).

```bibtex
@article{Cooler2019,
    author = {Abdennur, Nezar and Mirny, Leonid A},
    title = "{Cooler: scalable storage for Hi-C data and other genomically labeled arrays}",
    journal = {Bioinformatics},
    year = {2019},
    month = {07},
    doi = {10.1093/bioinformatics/btz540},
    url = {https://doi.org/10.1093/bioinformatics/btz540},
}
```

### License

BSD (3 Clause)

### Related projects

- Process Hi-C data with [distiller](https://github.com/open2c/distiller)!
- Downstream analysis with [cooltools](https://github.com/open2c/cooltools)!
- Visualize your cooler data with [HiGlass](http://higlass.io)!

