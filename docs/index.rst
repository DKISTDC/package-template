.. _package-template:

Welcome to SunPy Package Template's documentation!
====================================================

The SunPy package template is designed to help quickly create new Python packages within the SunPy ecosystem.

Getting Started
---------------

The SunPy Package template uses the `Cookiecutter
<http://cookiecutter.readthedocs.io/>`_ project to make it easier to get
started. To use the package template you need cookiecutter installed, depending
on how you have Python installed it can be obtained through either pip or
conda::

  conda install -c conda-forge cookiecutter gitpython

or::

  pip install cookiecutter gitpython

Cookiecutter works by taking a template (in this case the Astropy Package
Template) and asking you a series of :ref:`questions <options>` to create a set
of files and folders where your answers to the questions are pre-filled into the
correct places. The package template uses this to allow you to specify things
like your project's name as well as choose what parts and features of the
template you want to use.

To start a package with the package template run::

  cookiecutter gh:sunpy/package-template

This will prompt you with a series of questions about your project. See
the :ref:`options` page for more details on the various options.

If this is the first time you are rendering a template, you may want to take a
moment to examine the example files that have been included in the package.
These are examples of a pure-python module, a test script, a `Cython
<http://cython.org/>`_ module, and a sub-package, respectively.  These are
provided as examples of a standard way to lay these out. Once you understand
these or if you do not need them, you'll want to delete them
and later replace with your own as needed.

For further customization of your package including setting up testing and
documentation, read the :ref:`next-steps` for further information.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   options
   nextsteps
   updating



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. _Astropy: http://astropy.org
