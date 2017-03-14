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
        | |coveralls|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/reclient/badge/?style=flat
    :target: https://readthedocs.org/projects/reclient
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/osantana/reclient.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/osantana/reclient

.. |coveralls| image:: https://coveralls.io/repos/osantana/reclient/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/osantana/reclient

.. |version| image:: https://img.shields.io/pypi/v/reclient.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/reclient

.. |commits-since| image:: https://img.shields.io/github/commits-since/osantana/reclient/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/osantana/reclient/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/reclient.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/reclient

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/reclient.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/reclient

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/reclient.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/reclient


.. end-badges

A small library with helpers to create reliable HTTP REST client libraries

* Free software: BSD license

Installation
============

::

    pip install reclient

Documentation
=============

https://reclient.readthedocs.io/

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
