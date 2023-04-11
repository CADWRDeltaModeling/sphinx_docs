.. DWR's Delta Modeling Office's guidance on documentation in Sphinx
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. this next line is a tag to refer to a specific place in the \*.rst files
.. _home:

Main Page
========================

Headers are delineated in Sphinx by any successive character in this list = - ` . ; ' " ~ ^ > \ * + #
You can choose whichever order of headers, but you need to be consistent accross all \*.rst files. For simplicity's sake, use the order listed above, where "=" is the highest level header, then "-" and so on.

You can create links using `SCHISM <http://ccrm.vims.edu/schismweb/>`_ where "SCHISM" is the hyperlink display text.

An example of a built-out project is in this `github repository`_.

.. _github repository:  https://github.com/CADWRDeltaModeling/HelloSCHISM

To jump to a specific part of another \*.rst file you can use the following:

*	:ref:`Example Page <example>`
*	:ref:`Example Image <exampleimg>`

.. _pystart:

Python
------------------------
To compile the Sphinx \*.rst files into an HTML web page you need to create a sphinx environment.

If you are using anaconda/miniconda (recommended) navigate to this repository and enter the following command:

.. code-block:: console

   conda env create --name sphinx -f sphx_env.yaml

This creates a new environment called “sphinx” which contains the necessary packages to compile the webpage.

Table of Contents
--------------------------

.. toctree::
   :hidden:

   self

.. toctree::
   :maxdepth: 3
   :caption: Example Page

   example
   
   
Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`