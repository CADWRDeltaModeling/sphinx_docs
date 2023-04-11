.. DWR's Delta Modeling Office's guidance on documentation in Sphinx
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. this next line is a tag to refer to a specific place in the \*.rst files
.. _home:

Getting Started
========================

Here is some basic info needed to get started documenting in Sphinx.

Headers
------------------------

Headers are delineated in Sphinx by any successive character in this list 

= - ` . ; ' " ~ ^ > \ * + #

Sub-Headers
````````````````````````

You can choose whichever order of headers, but you need to be consistent accross all \*.rst files. For simplicity's sake, use the order listed above, where "=" is the highest level header, then "-", then "`", and so on.

Links
-------------------------
You can create links using `SCHISM <http://ccrm.vims.edu/schismweb/>`_ where "SCHISM" is the hyperlink display text.

An example of a built-out project is in this `Hello SCHISM GitHub repository`_ or in this `Bay-Delta SCHISM GitHub repository`_.

.. _Hello SCHISM GitHub repository:  https://github.com/CADWRDeltaModeling/HelloSCHISM
.. _Bay-Delta SCHISM GitHub repository:  https://github.com/CADWRDeltaModeling/BayDeltaSCHISM

To jump to a specific part of another \*.rst file you can use the following:

*	:ref:`Python Instructions <pystart>`
*   :ref:`Compiling rst files to HTML <compiling>`
*   :ref:`Linking webpage to GitHub repository <linkgit>`
*	:ref:`Example Image <exampleimg>`

Figures
--------------------------
.. _exampleimg:

.. figure:: /img/visit_velocity_vectors.png
   :alt: Hello SCHISM model velocity results
   :align: center

   *An example of some velocity outputs of HelloSCHISM*
   
Table of Contents
--------------------------
.. toctree::
   :caption: Main Page
   
   self

.. toctree::
   :numbered:
   :maxdepth: 2
   :caption: Compiling Instructions

   compile
   
   
Indices and tables
==================

* :ref:`genindex`
* :ref:`search`