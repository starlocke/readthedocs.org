Welcome to Read The Docs
========================

|build-status| |docs|

Purpose
-------

`Read the Docs`_ hosts documentation for the open source community. It supports
Sphinx_ docs written with reStructuredText_, and can pull from your Subversion_,
Bazaar_, Git_, and Mercurial_ repositories.

.. _Read the docs: http://readthedocs.org/
.. _Sphinx: http://sphinx.pocoo.org/
.. _reStructuredText: http://sphinx.pocoo.org/rest.html
.. _Subversion: http://subversion.tigris.org/
.. _Bazaar: http://bazaar.canonical.com/
.. _Git: http://git-scm.com/
.. _Mercurial: http://mercurial.selenic.com/

Documentation for RTD
---------------------

You will find complete documentation for setting up your project at `the Read
the Docs site`_.

.. _the Read the Docs site: http://read-the-docs.readthedocs.org

Quickstart for GitHub-Hosted Projects
-------------------------------------

By the end of this quickstart, you will have a new project automatically updated
when you push to GitHub.

#. Create an account on `Read the Docs`_.  You will get an email verifying your
   email address which you should accept within 7 days.

#. Log in and click on "Import".

#. Give your project a name, add the HTTPS link for your GitHub project, and
   select Git as your repository type.

#. Fill in the rest of the form as needed and click "Create".

#. On GitHub, navigate to your repository and click on "Settings".

#. In the sidebar, click on "Web Hooks & Services", then find and click on the
   "ReadTheDocs" service.

#. Check the "Active" setting and click "Update Settings".

#. All done.  Commit away and your project will auto-update.


.. |build-status| image:: https://img.shields.io/travis/rtfd/readthedocs.org.svg?style=flat
    :alt: build status
    :scale: 100%
    :target: https://travis-ci.org/rtfd/readthedocs.org

.. |docs| image:: https://readthedocs.org/projects/docs/badge/?version=latest
    :alt: Documentation Status
    :scale: 100%
    :target: https://readthedocs.org/projects/docs/
