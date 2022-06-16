# Neoscrypt Python Module

This package defines a simple Python module for the Neoscrypt PoW hash
function, as used by [Xaya](https://xaya.io/) and other blockchains.

Neoscrypt hash in C wrapped in python module

It can be installed or built with python 2 or 3. Just use the right python version to install or build.

# Install
python 2: `python setup.py install`
python 3: `python3 setup.py install`

# Build
python 2: `python setup.py build`
python 3: `python3 setup.py build`

# Using the module
`import neoscrypt`

In python 2 input data should be in string:
`data = '00'.decode('hex')`

In python 3 input data must be in bytes:
`data = b'\x00'`

`hashed = neoscrypt.getPoWHash(data)`
