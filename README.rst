hydropowerlib
==============

The hydropowerlib is designed to calculate feedin time series of run-of-the-river hydropower plants. The hydropowerlib is an out-take from the 
`feedinlib <https://github.com/oemof/feedinlib>`_ (hydropower, windpower and pv) to build up a community concentrating on hydropower models.

.. contents:: `Table of contents`
    :depth: 1
    :local:
    :backlinks: top

Introduction
============

Having water flow data sets you can use the hydropowerlib to calculate the electrical output of common hydropower turbines. 
Basic parameters for different types of turbine are provided with the library so that you can start directly using one of these parameter sets. Of course you are free to add your own parameter set.
For a quick start download the example water flow data and basic example file and execute it:

https://github.com/hydro-python/hydropowerlib/tree/master/example

Documentation
==============

Full documentation can be found at `readthedocs <http://hydropowerlib.readthedocs.org/en/latest/>`_. Use the project site of readthedocs to choose the version of the documentation. 

Contributing
==============

Clone/Fork: https://github.com/hydro-python/hydropowerlib

If you are interested in hydropower models and want to help improve the existing model do not hesitate to contact us.
As the hydropowerlib started with contributors from the `oemof developer group <https://github.com/orgs/oemof/teams/oemof-developer-group>`_ we use the same 
`developer rules <http://oemof.readthedocs.io/en/stable/developing_oemof.html>`_.


Installation
============

Install the hydropowerlib using pip3.

::

    pip3 install hydropowerlib

So far, the hydropowerlib is mainly tested on python 3.4 but seems to work down to 2.7.
Please see the `installation page <http://oemof.readthedocs.io/en/stable/installation_and_setup.html>`_ of the oemof documentation for complete instructions on how to install python on your operating system.

  
Optional Packages
~~~~~~~~~~~~~~~~~

To see the plots of the example file you should install the matplotlib package.

Matplotlib can be installed using pip3 but some Linux users reported that it is easier and more stable to use the pre-built packages of your Linux distribution.

http://matplotlib.org/users/installing.html

