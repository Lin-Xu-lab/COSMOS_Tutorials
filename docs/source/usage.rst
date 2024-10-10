Usage
=====

.. _installation:

Installation
------------

To use COSMOS, first install it using pip:

.. code-block:: console

   (.venv) $ git clone https://github.com/Lin-Xu-lab/COSMOS.git

Creating recipes
----------------

For example:

import pandas as pd
import numpy as np
import scanpy as sc
import matplotlib
import matplotlib.pyplot as plt
from umap import UMAP
import sklearn
import seaborn as sns
from COSMOS import cosmos
from COSMOS.pyWNN import pyWNN 
import warnings
warnings.filterwarnings('ignore')
random_seed = 20

