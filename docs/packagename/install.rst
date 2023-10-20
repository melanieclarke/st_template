Installation
------------

It is highly recommended that the user install packagename into a virtual
environment.  For example, use conda to create and activate a virtual environment
before following the installation steps::

    $ conda create -n packagename python
    $ conda activate packagename


The package can then be installed into this environment from source or via pip.
Either method will also download and install the required software dependencies.

Install via pip
~~~~~~~~~~~~~~~

To install the latest stable release via pip::

    $ pip install packagename


Install from source
~~~~~~~~~~~~~~~~~~~

To install the top-level package from source via GitHub::

    $ git clone https://github.com/spacetelescope/packagename
    $ pip install -e packagename
