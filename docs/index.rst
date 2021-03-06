JDAViz Documentation
====================

``jdaviz`` is a package of astronomical data analysis visualization
tools based on the Jupyter platform.  These GUI-based tools link data
visualization and interactive analysis.  They are designed to work
within a Jupyter notebook cell, as a standalone desktop application,
or as embedded windows within a website -- all with nearly-identical
user interfaces.

``jdaviz`` applications currently include tools for interactive
visualization of spectroscopic data.  SpecViz is a tool for
visualization and quick-look analysis of 1D astronomical spectra.
MOSViz is a visualization tool for many astronomical spectra,
typically the output of a multi-object spectrograph (e.g., JWST
NIRSpec), and includes viewers for 1D and 2D spectra as well as
contextual information like on-sky views of the spectrograph slit.
CubeViz provides of view of spectroscopic data cubes (like those to be
produced by JWST MIRI), along with 1D spectra extracted from the cube.


.. toctree::
  :maxdepth: 2

  installation.rst
  data_prep.rst
  dev/infrastructure.rst
  dev/ui_description.rst


Reference/API
=============

.. toctree::
   :maxdepth: 1

   reference/api.rst
