
The goal is a collection of demos and documentation for
[observable-jupyter](https://github.com/thomasballinger/observable-jupyter), a new Python library
that allows Python users to create interactive browser-based data visualizations...with JavaScript.

## Demo: Observable Plot

This Python notebook, [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pbogden/observable-jupyter-demos/blob/master/notebooks/observable_plot.ipynb),
demonstrates exploratory data analysis with
[Observable Plot](https://observablehq.com/@observablehq/plot), 
a new JavaScript library for EDA that's built with [D3](https://github.com/d3/d3#d3-data-driven-documents).
The Python notebook uses the observable-jupyter API to access the powerful Observable 
Plot library, which is 100% JavaScript.

**Yet another new Python plotting package?**

No. What's new is that observable-jupyter integrates
JavaScript data-viz capabilities directly into Python with a super simple API.
That makes the power of HTML5 data visualization readily accessible from Python.
The demo above shows how it's done with Observable Plot,
a library by [Mike Bostock](https://observablehq.com/@mbostock), creator of D3 and co-founder
of [Observable, Inc](http://observablehq.com).
But the capability is not restricted to Observable Plot.
You can take the same approach to provide direct Python access to all sorts of JavaScript data-viz libraries.

**Do you need to be front-end developer to customize things?**

No. Integrating JavaScript data viz into Python used to be hard, but not anymore -- 
you no longer need to be a front-end web dev to do it.
The demo shows how it's done.
And once things are set up, it's easy to create custom data visualizations in Python
without touching the JavaScript.

**It can't be that easy. What's the catch?**

Someone needs to set up a library-specific
[Observable notebook](https://www.google.com/search?q=observable+notebook&oq=observable+notebook&aqs=chrome..69i57j69i64j69i60l3j69i65.3681j0j7&sourceid=chrome&ie=UTF-8#kpvalbx=_XSUhYtfsCpiDytMPvsmf4Aw36) 
for use by observable-jupyter.
That notebook must expose the parameters and data variables needed on the JavaScript side.
You need to know some JavaScript to set it up, but it's not hard.
The demo above uses this [Observable notebook](https://observablehq.com/@pbogden/observable-plot-jupyter).
It's a very slightly modified fork of [Mike Bostock's original](https://observablehq.com/@observablehq/plot).
Parameters and data are specified in Python and then observable-jupyter sends it as JSON to the JavaScript 
side with a simple Python function call.
Once the Observable notebook is set up, anyone can use it.

**What's next?**

The goal is a collection of demos and documentation for doing data visualization in Python with observable-jupyter.
These demos will showcase a variety of cutting-edge JavaScript libraries ranging from interactive maps 
to 3-D scatterplots.
We'll show how to create the kinds of interactive visualizations that aren't currently possible in Python,
such as this [Mona Lisa Histogram](https://observablehq.com/@d3/mona-lisa-histogram).
And for those data scientists who know a little JavaScript,
we'll also create documentation that shows how to set up 
Observable notebooks so that they're easily usable with observable-jupyter.

## Related

* [robservable gallery](https://juba.github.io/robservable/articles/gallery.html)
* [discussions](https://github.com/thomasballinger/observable-jupyter/discussions/1)
* [examples](https://github.com/thomasballinger/observable-jupyter/discussions/2)
* Ideas being tossed around: 
  * Sphinx or other standard Python documentation format and likely hosted on https://readthedocs.org/
    * e.g., https://curtsies.readthedocs.io/en/latest/. 
  * exported Jupyter notebooks or colab notebooks might be a good fit for documenting the project
* [observable-jupyter-widget](https://github.com/thomasballinger/observable-jupyter-widget)
