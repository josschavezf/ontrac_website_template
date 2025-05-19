Calculating niche trajectories with ONTraC
==========================================

ONTraC (Ordered Niche Trajectory Construction) is a niche-centered, machine 
learning method for constructing spatially continuous trajectories. 

ONTraC differs from existing tools in that it treats a niche, rather than an 
individual cell, as the basic unit for spatial trajectory analysis. In this 
context, we define niche as a multicellular, spatially localized region where 
different cell types may coexist and interact with each other. 

ONTraC seamlessly integrates cell-type composition and spatial information by 
using the graph neural network modeling framework.

ONTraC generate niche cluster an assignment matrix as an intermediate result. 
It is possible for users to utilise the niche cluster information as spatial 
domains or other downstreaming analysis. The following section outlines the 
process for running ONTraC on stereo-seq data and visualising which niche 
cluster each cell belongs to.

Preparation
------------

- Install required packages and ONTraC

Please see the :doc:`installation` section for installation guidelines.

Running ONTraC
------------

.. code-block:: console

    ONTraC --meta-input data/stereo_seq_brain/original_data.csv --NN-dir output/stereo_seq_NN --GNN-dir output/stereo_seq_GNN --NT-dir output/stereo_seq_NT --device cuda -s 42 --lr 0.03 --hidden-feats 4 -k 6 --modularity-loss-weight 0.3 --regularization-loss-weight 0.1 --purity-loss-weight 300 --beta 0.03 2>&1 | tee log/stereo_seq.log


The input dataset and output files could be downloaded from `Zenodo <https://zenodo.org/records/11186620>`_


