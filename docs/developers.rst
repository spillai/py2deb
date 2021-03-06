Documentation for the py2deb API
================================

On this page you can find the complete API documentation of py2deb |release|.

A note about backwards compatibility
------------------------------------

On the one hand the py2deb project has been in development since April 2013, on
the other hand it was only made public in February 2015 (a couple of days at
the of writing :-). Also note that a 1.0 version number hasn't been reached
yet. What I mean to say is that I'm not committing to API stability yet. As the
project matures I will likely nominate a 1.0 version and decide to freeze the
API for backwards incompatible changes. That time hasn't come yet.

The Python API of py2deb
------------------------

Here are the relevant Python modules that make up py2deb:

.. contents::
   :local:

:py:mod:`py2deb` - Project metadata
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. automodule:: py2deb
   :members:

:py:mod:`py2deb.converter` - Package converter
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. automodule:: py2deb.converter
   :members:

:py:mod:`py2deb.package` - Package conversion model
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. automodule:: py2deb.package
   :members:

:py:mod:`py2deb.utils` - Utility classes/functions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. automodule:: py2deb.utils
   :members:

:py:mod:`py2deb.tests` - The test suite
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. automodule:: py2deb.tests
   :members:
