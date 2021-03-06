Changelog
=========


`1.0.0`_ - 2020-01-14
---------------------

**Features**

* Added a ``RETURN_HEADER`` setting, which will return the GUID as a header with the same name


**Improvements**

* Added a Django Rest Framework test and added DRF to the ``demoproj``

* Improved tests to also check for headers in the response

* Added tests for the new setting

* Added examples to ``README.rst`` and docs, to show how the log messages get formatted

* Added an API page to the docs

* Fixed the ``readthedocs`` menu bug



`0.3.1`_ - 2020-01-13
---------------------

**Improvements**

* Changed logging from f'strings' to %strings

* Pre-commit hooks added, including ``black`` and ``flake8``

* Added ``CONTRIBUTING.rst``

* Added github actions to push to ``PyPi`` with github tags



`0.3.0`_ - 2020-01-10
---------------------

**Features**

* Added a SKIP_CLEANUP setting

**Improvements**

* Improved all tests to be more verbose

* Improved the README with more information and a list of all the available settings


`0.2.3`_ - 2020-01-09
---------------------

**Improvements**

* Added tests written in `pytests`, 100% codecov

* Added Django2.2 and Django3 to github workflow as two steps

* Improved logging


`0.2.2`_ - 2019-12-21
---------------------

**Improvements**

* Removed the mandatory DJANGO_GUID settings in settings.py. Added an example project to demonstrate how to set the project up


`0.2.1`_ - 2019-12-21
---------------------

**Improvements**

* Workflow added, better docstrings, easier to read flow


`0.2.0`_ - 2019-12-21
---------------------

**Features**

* Header name and header GUID validation can be specified through Django settings

2019-12-20
------------------

* Initial release


.. _0.2.0: https://github.com/jonasks/django-guid/compare/0.1.2...0.2.0
.. _0.2.1: https://github.com/jonasks/django-guid/compare/0.2.0...0.2.1
.. _0.2.2: https://github.com/jonasks/django-guid/compare/0.2.1...0.2.2
.. _0.2.3: https://github.com/jonasks/django-guid/compare/0.2.2...0.2.3
.. _0.3.0: https://github.com/jonasks/django-guid/compare/0.2.3...0.3.0
.. _0.3.1: https://github.com/jonasks/django-guid/compare/0.3.0...0.3.1
.. _1.0.0: https://github.com/jonasks/django-guid/compare/0.3.0...1.0.0
