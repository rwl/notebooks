IPython Notebooks
=================

Setup virtual Python environment::

  $ virtualenv --system-site-packages ipynb


Install IPython and the notebook dependencies::

  $ pip install tornado pyzmq ipython


Run `IPython <http://ipython.org/>`_ notebook::

  $ ipython notebook --pylab inline
