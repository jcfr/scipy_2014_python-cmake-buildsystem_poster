Python CMake build system
=========================

A system for faster, straightforward cross-platform CPython builds across HPC, desktop, and mobile platforms with multiple build system generators and easy integration with C/C++/Fortran scientific computing libraries is described. 

[![DOI](https://zenodo.org/badge/5029/jcfr/scipy_2014_python-cmake-buildsystem_poster.svg)](http://dx.doi.org/10.5281/zenodo.17736)

Abstract
--------

While the [Python](http://www.python.org) language has seen multiple implementations across a number of languages as it has grown in popularity, the original C-implementation of Python, CPython, remains the most widely adopted implementation for scientific computing. This can be largely attributed to the ubiquitous presence of C-build systems on scientific computing platforms and the large number of libraries that have a C interface, which are bridged with C-Python Extension Modules.

[CMake](http://www.cmake.org) is a popular cross-platform build system that performs reliable system introspection and configuration of C/C++/Fortran builds.

The scientific computing community has tooled the python.org C-Python distribution with a CMake configuration so CPython can be built with the CMake build system. 

This enables cross-compilation for HPC clusters, the raspberry PI, and ARM architectures such as those found in mobile platforms, static and shared builds, and a static python with C extension modules included in the library, for example. Additionally, it provides capabilities such as faster compilation, cross-platform builds with multiple build system generators, easy integration with other CMake configured projects, and configuration and linking other scientific computing libraries into C-Extensions. It is a community maintained, open source project [available on Github](https://github.com/davidsansome/python-cmake-buildsystem) with nightly test results submitted to a [software quality dashboard](http://open.cdash.org/index.php?project=CPython).



Licensing
---------

Materials in this repository are distributed under the following licenses:

All Works of Art are licensed under the Creative Commons Attribution-ShareAlike 3.0.
See LICENSE_CC_BY_SA_30 file for details.
