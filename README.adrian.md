# Package Requirements

This package requires the following:
1. Python 3.7 (other versions of Python 3 should be fine but they are untested)
2. Pip -- the Python package installer
3. Any Python environment manager that can read a virtualenv requirements file
4. Any \*nix command line

# Installation

1. [Install Python 3](https://www.python.org/downloads/)
2. [Install Pip](https://pypi.org/project/pip/)
3. Install an environment manager like [virtualenv](https://virtualenv.pypa.io/en/latest/installation/)
4. Navigate to this repository's directory
`> cd /path/to/repo/dir`
5. Create a virtual environment with the Python version set to Python 3
```> virtualenv -p `which python3` movies```
6. Install the requirements
`> pip install -r requirements`
7. Run the `jupyter` notebook with
`> jupyter-notebook`
