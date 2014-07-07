Flask-Security
==============

.. image:: https://secure.travis-ci.org/mattupstate/flask-security.png?branch=develop

.. image:: https://pypip.in/v/Flask-Security/badge.png
    :target: https://pypi.python.org/pypi/Flask-Security/
    :alt: Latest Version

.. image:: https://coveralls.io/repos/mattupstate/flask-security/badge.png?branch=develop
    :target: https://coveralls.io/r/mattupstate/flask-security

.. image:: https://pypip.in/d/Flask-Security/badge.png
    :target: https://pypi.python.org/pypi//Flask-Security/
    :alt: Downloads

.. image:: https://pypip.in/license/Flask-Security/badge.png
    :target: https://pypi.python.org/pypi/Flask-Security/
    :alt: License

Flask-Security quickly adds security features to your Flask application.

Running tests
-------------

The tests are located under the ``test`` directory. To run the tests, you will
need to activate your virtualenv and install the required dependencies::

    pip install -r requirements.txt -r requirements-dev.txt -e .

Unit tests
^^^^^^^^^^

Unit tests are stored under the ``tests/unit/`` folder and can be run by calling
the following after activating your `virtualenv`::

    py.test --cov flask_security --cov-report term-missing tests/unit/

Integration tests
^^^^^^^^^^^^^^^^^

Integration tests are stored under ``tests/integration`` and depend on the
initialization of one or more integration testing environments. They
can be run by calling::

    py.test tests/integration/<environment>/

Each environment will have a corresponding ``README.rst`` outlining its
requirements.

Resources
---------

- `Documentation <http://packages.python.org/Flask-Security/>`_
- `Issue Tracker <http://github.com/mattupstate/flask-security/issues>`_
- `Code <http://github.com/mattupstate/flask-security/>`_
- `Development Version
  <http://github.com/mattupstate/flask-security/zipball/develop#egg=Flask-Security-dev>`_
