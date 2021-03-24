**Activate the virtual environment with Conda (at the command line)**

"""conda create --name {blockchain}"""

"""conda activate {blockchain}"""

**Activate the virtual environment at the command line**

creating VENV== """python3 -m venv {blockchain}"""

activating VENV== """source {blockchain}/bin/activate"""

**Install all packages**

"""pip3 install -r requirements.txt"""

**Running scripts from the command line**

normally when running a single script the command
"""python3 block.py"

With the introduction of packages and modules - alter syntax to invoke the module
"""python3 -m backend.blockchain.block"""

**Run the tests**

Make sure to activate the virtual environment

"""python3 -m pytest backend/tests""" - note pytest uses conventional syntax i.e. '/'