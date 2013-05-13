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

Run tests:

::

    $ bin/manage test stub_app -v 2
