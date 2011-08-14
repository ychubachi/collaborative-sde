.. include:: define.rst

.. _Cygwin: http://www.cygwin.com/
.. _setup.exe: http://www.cygwin.com/setup.exe

Cygwin
======

What is Cygwin?
~~~~~~~~~~~~~~~

Cygwin is a collection of tools which provide a Linux look and feel environment for Windows.

See `Cygwin`_ for more information.

Installing Cygwin
~~~~~~~~~~~~~~~~~
Create a directory for Cygwin under the user's home directory like |user home|.

Make two directories to prepare this installation.

#. |cygwin|
#. |cygwin packages|


Download `setup.exe`_ to |cygwin|.

Run setup.exe at |cygwin|.

- Choose "install from internet" option.
- Set |cygwin| to "Root directory".
- Set |cygwin packages| to "Local Package Directory".
- Use default to other options.

setup.exe automatically download related packages from internet.

Run Cygwin
~~~~~~~~~~
Run cygwin.bat at |cygwin|.

Installing required packages
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Run setup.exe again and move to "Select Packages" dialog.

Install following packages

- **python** under "All/Python"
- **git** under "All/Devel"

Note: Search text box will help to find these packages.

