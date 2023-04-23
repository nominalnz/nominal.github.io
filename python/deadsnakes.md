Helpful guide on maintaining multiple versions of Python in Ubuntu using deadsnakes. Also describes how to install `distutils`, `pip`, `venv` etc. for the new version. For whatever reason, these are not shipped by default.

[Managing Multiple Versions of Python on Ubuntu 20.04](https://hackersandslackers.com/multiple-python-versions-ubuntu-20-04): _Easily install and manage multiple versions of Python on Ubuntu 20.04 or newer._

`update-alternatives` used to specify which Python version to use. 

`update-alternatives --list python3` to see available versions of Python. 

`update-alternatives --config python3` to swap between versions of Python.
