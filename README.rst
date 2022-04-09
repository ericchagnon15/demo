========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/demo/badge/?style=flat
    :target: https://demo.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/ericchagnon15/demo/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/ericchagnon15/demo/actions

.. |requires| image:: https://requires.io/github/ericchagnon15/demo/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/ericchagnon15/demo/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/ericchagnon15/demo/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/ericchagnon15/demo

.. |version| image:: https://img.shields.io/pypi/v/demo.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/demo

.. |wheel| image:: https://img.shields.io/pypi/wheel/demo.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/demo

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/demo.svg
    :alt: Supported versions
    :target: https://pypi.org/project/demo

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/demo.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/demo

.. |commits-since| image:: https://img.shields.io/github/commits-since/ericchagnon15/demo/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/ericchagnon15/demo/compare/v0.0.0...main



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install demo

You can also install the in-development version with::

    pip install https://github.com/ericchagnon15/demo/archive/main.zip


Documentation
=============


https://demo.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
