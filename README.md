==========
python-farmhash
==========


Overview
========
This package provides bindings for the `Google's FarmHash <http://code.google.com/p/farmhash/>`_ .

Code specific to this project is covered by `The MIT License <http://opensource.org/licenses/MIT>`_

Install
=======
Currently, clone the repo and::
    $ cd python-farmhash
    $ sudo python setup.py Install


The package will be hosted on `PyPI <http://pypi.python.org/pypi/farmhash>`_::

    $ pip install farmhash
    $ easy_install farmhash

Usage
=====
The library is pretty simple to use::

    >>> import farmhash
    >>> print farmhash.hash64('abc')
    2640714258260161385
    >>>

For more details, use ipython::
    In [1]: import farmhash

    In [2]: farmhash.hash64withseed?
    Type:       builtin_function_or_method
    String Form:<built-in function hash64withseed>
    Docstring:
    Hash function for a string.  For convenience, a 64-bit seed is also hashed into the result. 
    example: print farmhash.hash64withseed('abc', 12345)
    13914286602242141520L



