# soname
Demonstrate SONAME handling by libtool projects

# Usage
* Make sure autoconf, automake and libtool are installed.
* Create the support files by running `autoreconf -i`.
* Configure the project: `./configure` (or use out of tree build)
* Build: `make`
* Install to a temporary directory: `make install DESTDIR=/tmp/soname`
