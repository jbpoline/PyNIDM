# PyNIDM

A Python library to manipulate the [Neuro Imaging Data Model](http://nidm.nidash.org). 

## Dependencies

* [graphviz](http://graphviz.org) (native package):
   * Fedora: `dnf install graphviz`
   * OS-X: `brew install graphviz`


## creating a conda environment and installing the library (tested with OSX)
  * `conda create -n pynidm_py35 python=3.5`
  * `source activate pynidm_py35`
  * `cd PyNIDM`
  * `pip install -e .`
  yes it looks like you already have `graphviz`, but OSX complains about `dot`
  * `conda install graphviz`
   you can try to run a test
  * `python nidm/experiment/tests/test_experiment.py`
