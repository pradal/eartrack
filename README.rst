.. contents::

========
EarTrack
========

An imaging library to detect and track future position of ear on maize plants.

=============
Documentation
=============
The documentation is available at `<https://eartrack.readthedoc.org>`_

A `Tutorial <http://nbviewer.ipython.org/urls/raw.github.com/openalea/eartrack/master/example/ear_tracking_tutorial.ipynb>`_ is available as a Jupyter Notebook.

===========================
Installation with Miniconda
===========================

Miniconda installation
----------------------

Follow official website instruction to install miniconda :

http://conda.pydata.org/miniconda.html

On Linux / Ubuntu / MacOS
-------------------------

Create virtual environment and activate it
..........................................

.. code:: shell

    conda create --name eartrack python
    source activate eartrack

Dependencies install
....................

.. code:: shell

    conda install  -c conda-forge numpy matplotlib opencv scikit-image
    conda install -c openalea openalea.deploy

(Optional) Package managing tools :

.. code:: shell

    conda install -c conda-forge notebook nose sphinx sphinx_rtd_theme


Eartrack install
................

.. code:: shell

    git clone https://github.com/openalea/eartrack.git
    cd eartrack
    python setup.py install --prefix=$CONDA_PREFIX

On Windows
----------

Create virtual environment and activate it
..........................................

.. code:: shell

    conda create --name eartrack python
    activate eartrack

Dependencies install
....................

.. code:: shell

    conda install -c conda-forge numpy matplotlib scikit-image opencv
    conda install -c openalea openalea.deploy

(Optional) Package managing tools :

.. code:: shell

    conda install -c conda-forge notebook nose sphinx sphinx_rtd_theme


Eartrack install
................

.. code:: shell

    git clone https://github.com/openalea/eartrack.git
    cd eartrack
    python setup.py install --prefix=%CONDA_PREFIX%


Authors
-------

* Nicolas Brichet <brichet@supagro.inra.fr>

License
-------

**EarTrack** is released under a `Cecill-C <http://www.cecill.info/licences/Licence_CeCILL-C_V1-en.html>`_ license.

