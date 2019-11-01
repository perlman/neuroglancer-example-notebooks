# Examples of using Neuroglancer with Jupyter

Original examples are from the 2019 NSF NeuroNex 3DEM Workshop in Austin, TX.

## Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/perlman/neuroglancer-example-notebooks/binder)

## Set up Jupyter in a new virtual environment (python/pip)

Note: `numpy` must be installed before cloud-volume.

```
python3 -m venv ENV
source ENV/bin/activate
pip install numpy
pip install -r reqs.txt
jupyter-lab
```

## Set up Jupyter in a new virtual environment (conda)

```
conda env create -f environment.yml
conda activate neuroglancer-demo
jupyter-lab
```

## References

* [Neuroglancer Repo](https://github.com/google/neuroglancer)
  * ... [Python Examples](https://github.com/google/neuroglancer/tree/master/python)

