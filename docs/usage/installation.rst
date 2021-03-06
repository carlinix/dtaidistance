Installation
------------

From PyPI
~~~~~~~~~

This packages is available on PyPI:

::

    $ pip install dtaidistance

Depending on your system, this might not install the C version. To guarantee installation of the C extensions (which enable much faster DTW alignment), follow the instructions in the "From Source" section below.


From Github
~~~~~~~~~~~

If you want to install the latest, unreleased version using pip:

::

    $ pip install git+https://github.com/wannesm/dtaidistance.git#egg=dtaidistance


From source
~~~~~~~~~~~

The library can also be compiled and/or installed directly from source.

* Download the source from https://github.com/wannesm/dtaidistance
* Compile the C extensions: ``python3 setup.py build_ext --inplace``
* Install into your site-package directory: ``python3 setup.py install``
