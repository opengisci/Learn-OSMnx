## Computational environment setup instructions

This demonstration was implemented using an Anaconda Python environment and JuptyerLab on Windows.

In order for OSMnx to work in a new environment, it is highly recommended to install with these instructions <https://osmnx.readthedocs.io/en/stable/installation.html> to create a new environment with the OSMNX package:

```
conda create -n ox -c conda-forge --strict-channel-priority osmnx
```

Or create a new environment and install OSMNX as the first package. This notebook was run with Python version 3.12.1 and osmnx version 1.8.1.
