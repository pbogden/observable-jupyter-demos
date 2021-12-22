
# observable-jupyter demos

A collection of Python demos using the very cool 
[observable-jupyter](https://github.com/thomasballinger/observable-jupyter),
which bridges the gap between [Observable notebooks](http://observablehq.com) (100% JavaScript) and Python!

## Observable Plot

Quick and easy charts: [Plot](https://observablehq.com/@observablehq/plot) is built with 
[D3](https://github.com/d3/d3#d3-data-driven-documents) and powered by 
[Observable](http://observablehq.com).
Try it in Colab: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pbogden/observable-jupyter-demos/blob/master/notebooks/observable_plot.ipynb)

Another new Python plotting package, you ask? No. It's true that Plot is a new open source 
plotting package by the amazing [Mike Bostock](https://observablehq.com/@mbostock)
creator of D3.
But it's not Python, it's 100% JavaScript.
You can use it with Python in Jupyter notebooks (and Colab) thanks to the remarkable 
[observable-jupyter](https://github.com/thomasballinger/observable-jupyter) Python package.

So is it Python or JavaScript, you ask? In a nutshell: As long as you can serialize your data and Plot options as JSON, 
you can use Observable Plot as easily as if it were a Python package.
The [Observable Plot](https://github.com/observablehq/plot#readme) API documentation is just as useful as
if it were a Python package.

Do I need to be front-end developer to figure out how to customize things for the Python side, you ask?
No, that's just the point -- it's super easy thanks to observable-jupyter and the Observable API.
You need an Observable notebook that exposes the JSON-encodable data and options needed by Plot. 
That's the point of this demo: my [Observable notebook](https://observablehq.com/@pbogden/observable-plot-jupyter).
But you don't need to be a front-end dev -- there's no package.json anywhere in the mix;-)
