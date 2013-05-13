To run this project do:

::

    $ cd djangorecipe_example/
    $ virtualenv --no-site-packages --distribute .
    $ source bin/activate
    $ python bootstrap.py
    $ bin/buildout
    $ bin/manage syncdb
    $ bin/manage runserver

Navigate to http://localhost:8000/admin and log in.

Run all tests:

::

    $ bin/manage test stub_app -v 2


Run a test by name:

::

    $ bin/manage test --select-tests=test_basic_addition
