lag_calc
========

.. currentmodule:: eqcorrscan.core.lag_calc
.. automodule:: eqcorrscan.core.lag_calc

Functions for generating pick-corrections from cross-correlations with a
template.  Originally this was designed for events detected by matched-filtering,
however you can use any well correlated events.  Based on the method of
`Shelly and Hardebeck (2010)`_.

.. _Shelly and Hardebeck (2010): http://onlinelibrary.wiley.com/doi/10.1029/2010GL043672/full

.. comment to end block

Functions
---------
.. autofunction:: lag_calc
.. autofunction:: xcorr_pick_family

.. comment to end block

Private Functions
-----------------
Note that these functions are not designed for public use and may change
at any point.

.. autofunction::  _concatenate_and_correlate
.. autofunction:: _prepare_data
.. autofunction:: _xcorr_interp
