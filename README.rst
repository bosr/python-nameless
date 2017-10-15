========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|

    * - tests
      - | |travis|

    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|


.. |docs| image:: https://readthedocs.org/projects/python-nameless/badge/?style=flat
    :target: https://readthedocs.org/projects/python-nameless
    :alt: Documentation Status
.. |travis| image:: https://travis-ci.org/bosr/python-nameless.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/bosr/python-nameless

.. |version| image:: https://img.shields.io/pypi/v/nameless.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/nameless

.. |commits-since| image:: https://img.shields.io/github/commits-since/bosr/python-nameless/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/bosr/python-nameless/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/nameless.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/nameless

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/nameless.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/nameless

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/nameless.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/nameless

.. end-badges

proj desc

* Free software: BSD license

Installation
============

::

    pip install nameless

Documentation
=============

https://python-nameless.readthedocs.io/

Development
===========

To run the all tests run::

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
