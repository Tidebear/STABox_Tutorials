.. STABox documentation master file, created by
   sphinx-quickstart on Tue May 28 23:22:23 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Installation
============


Software dependencies
---------------------
.. code-block:: python

   scanpy
   torch
   ttkbootstrap
   opencv-python
   rpy2
   gseapy
   PyYAML
   ...

The use of the mclust algorithm requires the rpy2 package and the mclust package. See https://pypi.org/project/rpy2/ and https://cran.r-project.org/web/packages/mclust/index.html for detail.


Installation
------------
Downloading STABox code from https://github.com/Tidebear/STABox

.. code-block:: python

   git clone https://github.com/zhanglabtools/STABox.git
   cd STABox


It's recommended to create a separate conda environment for running STABox

.. code-block:: python

   conda create -n env_STABox python=3.8
   conda activate env_STABox

Install R environment in python by conda

.. code-block:: python

   conda install -c conda-forge r-base


Other required packages are listed in STABox_env.yaml. Please note that we recommend that you install the appropriate version of pytorch and other packages that are not easy to install, depending on the configuration of your computer. (For pytorch installation requirements, see https://pytorch.org/)



