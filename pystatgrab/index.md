---
title: pystatgrab
description: a set of Python bindings for libstatgrab
---

pystatgrab
==========

* [What is pystatgrab?](#what-is-pystatgrab)
* [Current version](#current-version)
* [Downloading](#downloading)
* [Bug reporting and development](#bug-reporting-and-development)

What is pystatgrab?
-------------------

pystatgrab is a set of Python bindings for the [libstatgrab](/) library. It installs as a module and provides a set of function calls with identical names to the libstatgrab functions. The returned data types also map logically on to the structures returned by libstatgrab.

pystatgrab should work on any platform that libstatgrab will work on and supports both Python 2 and Python 3. Currently, pystatgrab requires version 0.91 or later of libstatgrab.

pystatgrab is licensed under the GNU LGPL.

Current version
---------------

The current release is [pystatgrab 0.7.3](https://github.com/libstatgrab/pystatgrab/releases/tag/PYSTATGRAB_0_7_3) released on 03 June 2024.

It regenerated the library using a newer version of Cython which provided support for more recent Python 3 versions.

Downloading
-----------

All versions of pystatgrab can be downloaded from [GitHub](https://github.com/libstatgrab/pystatgrab/releases). Downloads are signed using our key ([download here](/i-scream-dev.asc)):

~~~~
{% include i-scream-dev.key %}~~~~

For installation instructions see the [README](https://github.com/libstatgrab/pystatgrab/blob/master/README) file contained within the archive. If you're using [FreeBSD](https://www.freebsd.org) you can make use of the [devel/py-statgrab](https://www.freshports.org/devel/py-statgrab) port to install pystatgrab (and libstatgrab) for you.

Bug reporting and development
-----------------------------

Bugs should be reported on the [GitHub issues](https://github.com/libstatgrab/pystatgrab/issues) page. Please include as much information as possible.

If you want to submit changes please open a Pull Request.
