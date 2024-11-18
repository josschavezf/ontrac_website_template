Welcome to ONTraC (Ordered Niche Trajectory Construction)!
===================================

ONTraC (Ordered Niche Trajectory Construction) is a niche-centered, machine 
learning method for constructing spatially continuous trajectories. 

ONTraC differs from existing tools in that it treats a niche, rather than an 
individual cell, as the basic unit for spatial trajectory analysis. In this 
context, we define niche as a multicellular, spatially localized region where 
different cell types may coexist and interact with each other. 

ONTraC seamlessly integrates cell-type composition and spatial information by 
using the graph neural network modeling framework. Its output, which is called 
the niche trajectory, can be viewed as a one dimensional representation of the 
tissue microenvironment continuum. By disentangling cell-level and niche-level 
properties, niche trajectory analysis provides a coherent framework to study 
coordinated responses from all the cells in association with continuous tissue 
microenvironment variations.

Check out the :doc:`usage` section for further information.

Check out the :doc:`installation` section for installation guidelines.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   installation
   usage
   tutorials
