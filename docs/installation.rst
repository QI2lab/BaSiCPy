Installation
============

For Mac (Intel chip), Linux or WSL2 users
-----------------------------------------

Install from PyPI

.. code-block:: bash

   pip install basicpy

or install the latest development version

.. code-block:: bash

   git clone https://github.com/peng-lab/BaSiCPy.git
   cd BaSiCPy
   pip install .


PyTorch backend
---------------

BaSiCPy uses a PyTorch backend. The PyPI package depends on PyTorch, so a
plain ``pip install basicpy`` is enough for CPU usage on most platforms.

For GPU acceleration, install a PyTorch build that matches your CUDA or
platform requirements by following the `official PyTorch installation guide
<https://pytorch.org/get-started/locally/>`_, then install BaSiCPy:

.. code-block:: bash

   pip install torch
   pip install basicpy

On Apple Silicon, PyTorch provides native builds with MPS support. Install
PyTorch according to the official guide before installing BaSiCPy if you need
that acceleration path.

Install with dev dependencies
-----------------------------

One can use `venv` as:

.. code-block:: bash

   git clone https://github.com/peng-lab/BaSiCPy.git
   cd BaSiCPy
   python -m venv venv
   source venv/bin/activate
   pip install -e '.[dev]'

.. note::

   Test rebuild 2026-03-12
