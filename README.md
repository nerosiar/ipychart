ipychart
===============================

Wrapping the great Chart.js library into an ipywidget

Installation
------------

To install use pip:

    $ pip install ipychart
    $ jupyter nbextension enable --py --sys-prefix ipychart


For a development installation (requires npm),

    $ git clone https://github.com/nicohlr/ipychart.git
    $ cd ipychart
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix ipychart
    $ jupyter nbextension enable --py --sys-prefix ipychart

References
------------

- https://ipywidgets.readthedocs.io/en/latest/examples/Widget%20Custom.html
- https://blog.jupyter.org/authoring-custom-jupyter-widgets-2884a462e724