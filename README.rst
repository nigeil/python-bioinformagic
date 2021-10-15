========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-bioinformagic/badge/?style=flat
    :target: https://python-bioinformagic.readthedocs.io/
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/nigeil/python-bioinformagic.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/nigeil/python-bioinformagic

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/nigeil/python-bioinformagic?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/nigeil/python-bioinformagic

.. |requires| image:: https://requires.io/github/nigeil/python-bioinformagic/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/nigeil/python-bioinformagic/requirements/?branch=master

.. |version| image:: https://img.shields.io/pypi/v/bioinformagic.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/bioinformagic

.. |wheel| image:: https://img.shields.io/pypi/wheel/bioinformagic.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/bioinformagic

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/bioinformagic.svg
    :alt: Supported versions
    :target: https://pypi.org/project/bioinformagic

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/bioinformagic.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/bioinformagic

.. |commits-since| image:: https://img.shields.io/github/commits-since/nigeil/python-bioinformagic/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/nigeil/python-bioinformagic/compare/v0.0.0...master



.. end-badges

Putting the info back into bioinformatics.

* Free software: Apache Software License 2.0

Installation
============

::

    pip install bioinformagic

You can also install the in-development version with::

    pip install https://github.com/nigeil/python-bioinformagic/archive/master.zip


Documentation
=============


https://python-bioinformagic.readthedocs.io/


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
