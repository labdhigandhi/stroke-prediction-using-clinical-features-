
1.Download the .ipynb file.


A python package providing an easy way to explicitly import Jupyter Notebooks files (.ipynb) the same way you would import regular .py files :

2.Installation

You can install ipynb with:

pip install ipynb


3.Importing a notebook

Full import

You can do a 'full' import - this has the same semantics of importing a .py file. All the code in the .ipynb file is executed, and classes/functions/variables in the top level are available for use.

If you have a notebook file named project.ipynb, you can import it via:

import ipynb.fs.full.project

You can use the from ... import .. too.

from ipynb.fs.full.project import X, Y, X
