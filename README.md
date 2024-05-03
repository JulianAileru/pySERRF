# pySERRF
Python implementation of the Systematic Error Removal Using Random Forest (SERRF) algorithm.
SERRF is a qc-based sample normalization method designed for large-scale untargeted metabolomics data.
The method was developed by the Fan et al. in 2015 (see https://slfan2013.github.io/SERRF-online/).
This is simply an attempt to port its functionality from R to python.
The package structure is based on SKlearn's transformers, with fit and transform methods.

TODO: Implement cross-validation
TODO: Add documentation
TODO: Add CLI