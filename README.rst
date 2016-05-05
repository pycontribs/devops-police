========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |codecov|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/devops-police/badge/?style=flat
    :target: https://readthedocs.org/projects/devops-police
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/ssbarnea/devops-police.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/ssbarnea/devops-police

.. |requires| image:: https://requires.io/github/ssbarnea/devops-police/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/ssbarnea/devops-police/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/ssbarnea/devops-police/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/ssbarnea/devops-police

.. |version| image:: https://img.shields.io/pypi/v/devops-police.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/devops-police

.. |downloads| image:: https://img.shields.io/pypi/dm/devops-police.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/devops-police

.. |wheel| image:: https://img.shields.io/pypi/wheel/devops-police.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/devops-police

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/devops-police.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/devops-police

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/devops-police.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/devops-police


.. end-badges

DevOps Police bot that does boring stuff.

* Free software: BSD license

Installation
============

::

    pip install devops-police

Documentation
=============

https://devops-police.readthedocs.io/

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
