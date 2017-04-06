This repository demonstrates an issue that exists in Bokeh 0.12.5 (and other
versions).

Custom models created in a Jupyter notebook are not able to be used unless
`output_notebook()` is called _after_ the model is created.  The
implementation of the custom model is just a copy of the `Line` model.

