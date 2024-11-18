Tutorials
=====

Niche clusters
----------------

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

