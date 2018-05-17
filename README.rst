DKIST package template
======================

.. image:: http://img.shields.io/badge/powered%20by-SunPy-orange.svg?style=flat
    :target: http://www.sunpy.org
    :alt: Powered by SunPy Badge

This is the template for DKIST Python packages.

For more information, see:

* The `documentation for the sunpy template  <http://docs.sunpy.org/projects/package-template/en/latest/>`_
* `This template's Github code repository <https://github.com/dkistdc/package-template>`_


Using this package template
---------------------------

Using cookiecutter
^^^^^^^^^^^^^^^^^^

This package template makes use of the `cookiecutter
<https://cookiecutter.readthedocs.io/en/latest/index.html>`__ package to make it
easier to get started with the package template. You will need to `install cookiecutter <https://cookiecutter.readthedocs.io/en/latest/installation.html>`__ which can
be done easily using conda or pip::

  conda install -c conda-forge cookiecutter gitpython

  pip install cookiecutter gitpython


Once you have cookiecutter installed you can run::

  cookiecutter gh:dkistdc/package-template

Which will ask you a series of questions to configure your package.

Improving the package template
------------------------------

If you want to modify this package template to add or fix things, the folder that
the user ends up with is ``{{ cookiecutter.package_name }}`` in this
repository. Everything in the repository that is not in this folder is not part
of the template that the user will have rendered.

For further information on writing templates for cookiecutter see `the cookiecutter docs <https://cookiecutter.readthedocs.io/en/latest/first_steps.html>`__.


Attribution
===========

This package template is a derivative of the sunpy package template which is
a derivative of the astropy package template, thanks astropy!
