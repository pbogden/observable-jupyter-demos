
# observable-jupyter demos

A collection of Python demos using the very cool 
[observable-jupyter](https://github.com/thomasballinger/observable-jupyter),
which bridges the gap between [Observable notebooks](http://observablehq.com) (100% JavaScript) and Python!

## Observable Plot

This is the first demo.  Quick and easy charts using: [Observable Plot](https://observablehq.com/@observablehq/plot), 
which is built with [D3](https://github.com/d3/d3#d3-data-driven-documents) and powered by 
[Observable](http://observablehq.com).
Try it in Colab: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pbogden/observable-jupyter-demos/blob/master/notebooks/observable_plot.ipynb)

## Not-so-FAQ

**Another new Python plotting package?** No. It's true that Plot is a new open source 
plotting package by the amazing [Mike Bostock](https://observablehq.com/@mbostock),
creator of D3.
But it's not Python, it's 100% JavaScript.
You can use it with Python in Jupyter notebooks (and Colab) thanks to the remarkable 
[observable-jupyter](https://github.com/thomasballinger/observable-jupyter) Python package by
Thomas Ballinger.

**So is it Python or JavaScript?** Both. Observable Plot is pure JavaScript, but you don't need to know
JavaScript to use it. You can use Plot as if it were pure Python. 
In a nutshell: As long as you can serialize your data and Plot options as JSON (that's not very restrictive),
you can use Observable Plot as easily as if it were a Python package.
And the beautiful [Observable Plot API documentation](https://github.com/observablehq/plot#readme) is just 
as useful for Python programmers as if it were a Python package.

**Do I need to be front-end developer to customize things from the Python side?**
No, that's just the point of the demo -- it's super easy to customize Observable Plot charts in 
Jupyter notebooks (or Colab) without touching any JavaScript.
Granted, someone needs to set up an Observable notebook that exposes the JSON-encodable data and options 
needed by Plot. But that's not a big deal.
That's what I did for this demo: my [Observable notebook](https://observablehq.com/@pbogden/observable-plot-jupyter).
You don't need to be a front-end dev -- there's no package.json anywhere in the mix;-)
