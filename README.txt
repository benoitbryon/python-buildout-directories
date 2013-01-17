####################
Buildout directories
####################

This project illustrates an article about buildout directories:

http://www.marmelune.net/en/python/buildout/tidy-buildout-directories/

To run the demo:

.. code-block:: sh

  # Get the code.
  git clone https://github.com/benoitbryon/python-buildout-directories
  cd python-buildout-directories/

  # In this example, we need to prepare some directories.
  mkdir -p lib/buildout
  mkdir -p lib/buildout/downloads

  # Bootstrap zc.buildout, i.e. install it.
  python bootstrap.py --distribute

  # Run zc.buildout.
  bin/buildout -N

  # Look at the result.
  ls -al ./
