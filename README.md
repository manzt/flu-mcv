# flu-mcv
Multiple coordinated views of flu data

Dependencies 
---
* JupyterLab 
* pandas 
* numpy
* [`altair`](https://altair-viz.github.io/index.html)

Setup & Installation
---
To create visualizations with Altair, you must have the Altair package and a frontend renderer (ie. JupyterLab, Jupyter Notebook, or Colab). Specific installation instructions are described in the [Altair documentation](https://altair-viz.github.io/getting_started/installation.html) for each of these renderers. This notebook was created in JupyterLab.

Copy the `flunet2010_11countries.csv` into the repo.

Observable notebook
---
While `altair` offers a convienient API to quickly generate interactive plots, there are limitations in rendering and Vega-Lite may not allow for desired customization (specifically in geo-projections). However, you are able to open any chart in the [Vega-Editor](https://vega.github.io/editor/#/) from Jupyter Lab and edit the Vega-Lite and even the compiled Vega schemas. I took the compiled Vega and Vega-Lite schemas from this notebook and rendered them in an [Observable notebook](https://beta.observablehq.com/@manzt/flu-mcv). I was able to change the schemas, specifically for the geo-projection, to build further customizable visualizations.
