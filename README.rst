========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-geodt/badge/?style=flat
    :target: https://python-geodt.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/softwareengineerprogrammer/python-geodt/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/softwareengineerprogrammer/python-geodt/actions

.. |codecov| image:: https://codecov.io/gh/softwareengineerprogrammer/python-geodt/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://app.codecov.io/github/softwareengineerprogrammer/python-geodt

.. |version| image:: https://img.shields.io/pypi/v/geodt.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/geodt

.. |wheel| image:: https://img.shields.io/pypi/wheel/geodt.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/geodt

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/geodt.svg
    :alt: Supported versions
    :target: https://pypi.org/project/geodt

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/geodt.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/geodt

.. |commits-since| image:: https://img.shields.io/github/commits-since/softwareengineerprogrammer/python-geodt/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/softwareengineerprogrammer/python-geodt/compare/v0.0.0...main



.. end-badges

GeoDT

* Free software: BSD 3-Clause License

Installation
============


You can install the in-development version with::

    pip install https://github.com/softwareengineerprogrammer/python-geodt/archive/main.zip


Documentation
=============


https://python-geodt.readthedocs.io/


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
