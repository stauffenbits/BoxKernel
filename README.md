box_kernel
===========

``box_kernel`` is a simple example of a Jupyter kernel. This repository
complements the documentation on wrapper kernels here:

http://jupyter-client.readthedocs.io/en/latest/wrapperkernels.html

Installation
------------
To install ``box_kernel`` from PyPI::

    pip install box_kernel
    python -m box_kernel.install

Using the Echo kernel
---------------------
**Notebook**: The *New* menu in the notebook should show an option for an Echo notebook.

**Console frontends**: To use it with the console frontends, add ``--kernel echo`` to
their command line arguments.