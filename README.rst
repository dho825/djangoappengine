Djangoappengine, a Django database backend for App Engine
=========================================================
#This version:

- merged devappserver2 branch with master (from commit: 5c4ef57)
- added cloud_storage storages.py commits to support Google Cloud Storage (from commit: 4ba8342)
- tbd

#Original:

Documentation at http://djangoappengine.readthedocs.org/

Djangoappengine allows you to use App Engine's datastore with
Django. It provides the necessary plumbing to query the datastore, and
custom management commands for deploying and running the SDK.

:master:
    .. image:: https://secure.travis-ci.org/django-nonrel/djangoappengine.png?branch=master
        :target: https://travis-ci.org/django-nonrel/djangoappengine

Contributing
------------
You are highly encouraged to participate in the development, simply use
GitHub's fork/pull request system.

If you don't like GitHub (for some reason) you're welcome
to send regular patches to the mailing list.

:Mailing list: http://groups.google.com/group/django-non-relational
:Bug tracker: https://github.com/django-nonrel/djangoappengine/issues
:License: 3-clause BSD, see LICENSE
:Keywords: django, app engine, orm, nosql, database, python
