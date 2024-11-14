.. rubix documentation master file, created by
   sphinx-quickstart on Thu Oct 10 13:33:35 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to RUBIX's documentation!
=================================

RUBIX is a tested and modular Open Source tool developed in JAX, designed to forward model IFU cubes of galaxies from cosmological hydrodynamical simulations.
The code automatically parallelizes computations across multiple GPUs, demonstrating performance
improvements over state-of-the-art codes. For further details see the publications or the documentation of the individual functions.

Currently the following functionalities are provided:

- Generate mock IFU flux cubes for stars from IllustrisTNG50

- Generate mock photometric images for stars for different filter curves

- Use different stellar population synthesis models

- Use MUSE as telescope instrument (and some other instruments)


Currently the code is under development and is not yet all functionality is available.
We are working on adding more features and improving the code, espectially we work on the following features:

- Adding support for more simulations

- Adding support for more telescopes

- Adding gas emission lines and gas continuum

- Adding dust attenuation

- Adding support for gradient calculation

If you are interested in contributing to the code or have ideas for further features, please contact us via a github issue.
If you use the code in your research, please cite the following paper: ???


.. toctree::
   :maxdepth: 1
   :caption: RUBIX documentation:

   self
   installation
   versions
   publications
   license

Notebooks
===================

.. toctree::
   :maxdepth: 1
   :caption: Notebooks:

   notebooks/create_rubix_data.ipynb
   notebooks/pipeline_demo.ipynb
   notebooks/rubix_pipeline_single_function.ipynb
   notebooks/rubix_pipeline_stepwise.ipynb
   notebooks/cosmology.ipynb
   notebooks/telescope.ipynb
   notebooks/spaxel_assignment.ipynb
   notebooks/ssp_template.ipynb
   notebooks/psf.ipynb

Code base documentation
=======================

.. toctree::
   :maxdepth: 3
   :caption: Code documentation:

   rubix.core
   rubix.cosmology
   rubix.galaxy
   rubix.pipeline

   rubix.spectra
   rubix.telescope

   rubix.utils
