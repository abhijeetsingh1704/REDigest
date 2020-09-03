# REDigest
REDigest: a Python GUI for *In-Silico* Restriction Digestion Analysis for Gene or Complete Genome Sequences

## Dependencies
REDigest is written in **Python3**, not adapted for python2 and its dependencies.

To use REDigest, following dependencies must be installed, (for python3, version ≥) 

1. tkinter (8.6)
2. Biopython (1.77)
3. Pandas (1.1.1)
4. Matplotlib (3.3.1)

## Running REDigest

### From source

In order to keep the REDigest requirements from clogging up the system dirs, it is recommended to install these in a virtual environment. This is also recommended in order to keep required packages at their proper versions.

```
# make the virtual environment
python3 -m venv venv

# activate it (Linux/Mac)
source venv/bin/activate

# (or) activate it (Windows)
venv\bin\activate.bat

# install required packages
pip install -r requirements.txt
```

After setting up the virtual environment, it simply needs to be activated before running the software. After activating, the software is executed by running
```
python REDigestGUI.py
```

### Using binary releases

Binary releases will be provided under the [Releases](releases) tab.
