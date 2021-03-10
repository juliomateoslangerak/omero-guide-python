# User guides for the OMERO Python API
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/juliomateoslangerak/omero-guide-python.git/Cavalli_demo?filepath=notebooks)

[![Documentation Status](https://readthedocs.org/projects/omero-guide-python/badge/?version=latest)](https://omero-guides.readthedocs.io/en/latest/python/docs/index.html)

[![Actions Status](https://github.com/ome/omero-guide-python/workflows/repo2docker/badge.svg)](https://github.com/ome/omero-guide-python/actions)

[![Actions Status](https://github.com/ome/omero-guide-python/workflows/sphinx/badge.svg)](https://github.com/ome/omero-guide-python/actions)

The documentation is deployed at [Use Python API](https://omero-guides.readthedocs.io/en/latest/python/docs/index.html)


This guide demonstrates how to use the OMERO Python API.

To run the notebooks, you can either [run on mybinder.org](https://mybinder.org/v2/gh/ome/omero-guide-python/master?filepath=notebooks) or build locally with [repo2docker](https://repo2docker.readthedocs.io/).

To build locally:

 * Install [Docker](https://www.docker.com/) if required
 * Create a virtual environment and install repo2docker from PyPI.
 * Clone this repository
 * Run ``repo2docker``. 
 * Depending on the permissions, you might have to run the command as an admin


```
pip install jupyter-repo2docker
git clone https://github.com/ome/omero-guide-python.git
cd omero-guide-python
repo2docker .
```

See also [setup.rst](https://github.com/ome/omero-guide-python/blob/master/docs/setup.rst)


This is a Sphinx based documentation. 
If you are unfamiliar with Sphinx, we recommend that you first read 
[Getting Started with Sphinx](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html).
