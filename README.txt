####################
Buildout directories
####################

This project illustrates and article about buildout directories.

To run the demo:

.. code-block:: sh

  # Get the code.
  git clone https://github.com/benoitbryon/python-buildout-directories
  cd python-buildout-directories/

  # Bootstrap zc.buildout, i.e. install it.
  mkdir -p lib/buildout
  python bootstrap.py --distribute

  # Run zc.buildout.
  bin/buildout -N

  # Look at the result.
  ls -al ./
