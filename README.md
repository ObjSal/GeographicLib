GeographicLib
=============

A C++ library for geographic projections.


# Install
## Installation using the autoconfigure tools

The method works on most Unix-like systems including Linux and Mac OS X. Here are the steps to compile and install [GeographicLib](http://geographiclib.sourceforge.net/html/namespaceGeographicLib.html):

* Unpack the source, running
```
tar xfpz GeographicLib-1.44.tar.gz
```
then enter the directory created
```
cd GeographicLib-1.44
```
* Create a separate build directory and enter it, for example,
```
mkdir BUILD
cd BUILD
```
* Configure the software, specifying the path of the source directory, with
```
../configure
```
* By default GeographicLib will be installed under /usr/local. You can change this with, for example
```
../configure --prefix=/tmp/geographic
```
* Compile and install the software with
```
make
make install
```
The headers, library, and utilities are installed in the include/GeographicLib, lib, and bin directories under prefix. For documentation, open [share/doc/GeographicLib/html/index.html](http://geographiclib.sourceforge.net/html/index.html) in a web browser.

# Disclaimer
* This project and instructions were downloaded from [http://geographiclib.sourceforge.net/](https://sourceforge.net/projects/geographiclib/files/distrib)
* To try out an online solution check out [Online geographic coordinate conversions using the GeoConvert utility](http://geographiclib.sourceforge.net/cgi-bin/GeoConvert)

