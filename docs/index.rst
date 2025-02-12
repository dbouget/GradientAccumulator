:github_url: https://github.com/andreped/GradientAccumulator/tree/main/docs

GradientAccumulator
-------------------

GradientAccumulator is a lightweight and low-code library for enabling gradient accumulation
techniques in TensorFlow. It is designed to be integrated seemlessly and be compatible to
the most commonly used training pipelines for deep neural networks. To make it work with
modern techniques such as batch normalization and gradient clipping, custom implementations
have been made which can be used as drop-in replacement for existing implementations.
custom implementations.

Installation
------------

The latest release of GradientAccumulator can be installed from
`PyPI <https://pypi.org/project/gradient-accumulator/>`_ using

``pip install gradient-accumulator``

You may also install directly from GitHub, using the following command. This
can be used to obtain the most recent version of GradientAccumulator.

``pip install git+https://github.com/andreped/GradientAccumulator``

Note that GradientAccumulator is built on top of `TensorFlow <https://www.tensorflow.org/>`_, which is installed during
installation if no existing version is found.

.. toctree::
   :glob:
   :caption: Background
   :maxdepth: 2

   background/*

.. toctree::
   :glob:
   :caption: Examples
   :maxdepth: 2

   examples/*

.. toctree::
   :glob:
   :caption: Frequently Asked Questions
   :maxdepth: 2

   faq/*


.. toctree::
   :caption: API Documentation
   :maxdepth: 2

   api

The Team
--------

.. image:: https://www.indianbureaucracy.com/wp-content/uploads/2015/12/SINTEF_logo_indianbureaucracy.jpg
   :width: 20%
   :align: center

The development of GradientAccumulator is led by André Pedersen with
coworkers at the `SINTEF Medical Image Analysis <https://www.sintef.no/en/digital/departments-new/department-of-health-research/>`_
research group. We are also very grateful to the open source community for
contributing ideas, bug fixes, and issues.

Support
-------

If you are having issues, please let us know by filing an issue on our
`issue tracker <https://github.com/andreped/GradientAccumulator/issues>`_ or 
making a discussion in the dedicated `Discussions tab <https://github.com/andreped/GradientAccumulator/discussions>`_.


License
-------

GradientAccumulator is licensed under the `MIT License <https://github.com/andreped/GradientAccumulator/blob/main/LICENSE>`_.


Indices and Tables
==================

* :ref:`genindex`
