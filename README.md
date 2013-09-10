CPUCompare
==========

A GTK+ application to make comparisons between CPU models.
Copyright 2013 Fabio Castelli <webreg(at)vbsimple.net>
License GPL-2+

System Requirements
===================

Python 2.x (developed and tested for Python 2.7.5)
GTK+3.0 libraries for Python 2
SQLite3 library for Python 2 (usually shipped with Python distribution)
Distutils library for Python 2 (usually shipped with Python distribution)

Installation
============

A distutils installation script is available to install from the sources.
To install in your system please use:
cd /path/to/folder
python2 setup.py install

To install the files in another path instead of the standard /usr prefix use:
cd /path/to/folder
python2 setup.py install --root NEW_PATH

Usage
======

When the application is not installed please use:
cd /path/to/folder
python2 cpucompare.py

If the application was installed simply use the cpucompare command.
