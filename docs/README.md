
The goal is to create a collection of Python data-visualization demos and documentation for using
[observable-jupyter](https://github.com/thomasballinger/observable-jupyter), a new Python library
that bridges the gap between JavaScript and Python!

## Example: Observable Plot

This Python notebook, [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pbogden/observable-jupyter-demos/blob/master/notebooks/observable_plot.ipynb),
demonstrates exploratory data analysis with
[Observable Plot](https://observablehq.com/@observablehq/plot), 
a JavaScript library built with [D3](https://github.com/d3/d3#d3-data-driven-documents).

* **Yet another new Python plotting package?**
  * No. What's new is that observable-jupyter integrates
JavaScript data-viz capabilities directly into Python with a super simple API.
The demo above shows how it's done with Observable Plot,
a charting library by [Mike Bostock](https://observablehq.com/@mbostock), creator of D3 and co-founder
of [Observable, Inc](http://observablehq.com).
But you use the same approach to use all sorts of JavaScript data-viz libraries directly from Python.

### Do I need to be front-end developer to customize things on the Python side?

No. Integrating JavaScript into Python used to be hard, but not anymore -- 
you no longer need to be a front-end web dev to do it.
The purpose of the demo is to show how it's done. 
Once things are set up, it's easy to create custom data visualizations in Jupyter notebooks (or Colab) 
without touching the JavaScript.

### It can't be that easy. What's the catch?

Someone needs to set up the Observable notebook to expose the parameters and data variables
needed by the JavaScript library. You need to know JavaScript to set it up, but it's not hard.
That's the purpose of this [Observable notebook](https://observablehq.com/@pbogden/observable-plot-jupyter).
It's a very slightly modified fork of [Mike Bostock's original](https://observablehq.com/@observablehq/plot).
Parameters and data are specified in Python and then sent as JSON to the JavaScript by a simple
Python function call using the observable-jupyter API.

**What's next?**
The goal is to create a collection of Observable notebooks that enable cutting-edge data viz in Python
using a variety of JavaScript libraries, along with documentation that makes it easy to use by for data 
scientists who know only Python.
