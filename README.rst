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

The tests are located under the ``tests`` directory. Additional dependencies
to have all tests pass include a running `MongoDB`_ instance. The MongoDB
database URI can be configured with the ``--mongodb_uri`` argument to
``py.test``.

Databases, of the form ``'flask_security_test_<timestamp>``, will be created
and torn down by the test infrastructure.

Python dependencies can be installed into an activated virtualenv::

    pip install -r requirements.txt -r requirements-dev.txt -e .

`pytest`_ is used to run the tests::

    py.test --cov flask_security --cov-report term-missing tests/

Various custom options have been added to aid test configurability. An
exhaustive list of these options can be found in the ``custom options``
section of the ``py.test`` help::

    py.test --help

Resources
---------

- `Documentation <http://packages.python.org/Flask-Security/>`_
- `Issue Tracker <http://github.com/mattupstate/flask-security/issues>`_
- `Code <http://github.com/mattupstate/flask-security/>`_
- `Development Version
  <http://github.com/mattupstate/flask-security/zipball/develop#egg=Flask-Security-dev>`_

.. _MongoDB: http://www.mongodb.org/
.. _pytest: http://pytest.org/
