Installation
=====

Step 1: Create and activate a conda env (recommended)
------------

ONTraC supports Python 3.10, 3.11, and 3.12 for now

.. code-block:: console

   conda create -y -n ONTraC python=3.11  
   conda activate ONTraC

Add this kernel to jupyter (recommended)

.. code-block:: console

   pip install ipykernel
   python -m ipykernel install --user --name ONTraC --display-name "Python 3.11 (ONTraC)"


Step 2: Install ONTraC
----------------

Using pip

.. code-block:: console

   pip install ONTraC
   python -m ipykernel install --user --name ONTraC --display-name "Python 3.11 (ONTraC)"


Use this command if you want to visualise the results by `ONTraC_analysis`.

.. code-block:: console

   pip install ONTraC[analysis]


Using conda

NOTE: For ARM-based macOS, we recommend installing via pip for now, as the 
dependency package, pytorh-geometric, does not have a conda build for it. 
NOTE: For x86-based macOS, conda install only supports Python 3.10 and 3.11 for 
now. WARNING: Installing with conda can be very slow.

.. code-block:: console

   conda install -c gyuanlab -c pytorch -c pyg -c default -c nvidia -c conda-forge ontrac


Install the development version from GitHub

.. code-block:: console

   git clone git@github.com:gyuanlab/ONTraC.git .
   cd ONTraC
   pip install .
   pip install ".[analysis]"


Optional dependencies
----------------

Deconvolution


STdeconvolve is a reference-free cell-type deconvolution method. Please install 
through the following command if you want to use it in the preprocessing step 
when analyzing low resolution data.

.. code-block:: console

   conda install bioconda::bioconductor-stdeconvolve -y


