Pylians3 documentation
======================

Pylians stands for **Py**\thon **li**\braries for the **a**\nalysis of **n**\umerical **s**\imulations. They are a set of python libraries, written in python, cython and C, whose purposes is to facilitate the analysis of numerical simulations (both N-body and hydrodynamic). Pylians3 evolved from `Pylians <https://github.com/franciscovillaescusa/Pylians>`__ to support python3. Among other things, they can be used to:

- Compute density fields
- Compute power spectra
- Compute bispectra
- Compute correlation functions
- Identify voids
- Populate halos with galaxies using an HOD
- Apply HI+H2 corrections to the output of hydrodynamic simulations
- Make 21cm maps
- Compute DLAs column density distribution functions
- Plot density fields and make movies

`Pylians <https://en.wikipedia.org/wiki/Nestor_(mythology)>`__ were the native or inhabitant of the Homeric town of Pylos. 


.. toctree::
   :maxdepth: 1
   :caption: Installation

   linux
   mac

.. _density_fields:
.. toctree:: 
   :maxdepth: 2
   :caption: Density fields

   standard_fields
   marked_fields
   field_interpolation
   hydro_sims_fields2D
   hydro_sims_fields3D
	     
.. toctree::
   :maxdepth: 2
   :caption: Functionalities

   Pk
   xi
   Bk
   voids
   smoothing
   RSD

.. toctree::
   :maxdepth: 2
   :caption: Neutral hydrogen
      
.. toctree:: 
   :maxdepth: 2
   :caption: Miscellaneous

   plots
   cosmology
   gaussian_fields
   integrals
   gadget

.. toctree::
   :maxdepth: 2
   :caption: Other

   license
   contact
