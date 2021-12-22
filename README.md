
# observable-jupyter demos

A collection of Python demos using the very cool 
[observable-jupyter](https://github.com/thomasballinger/observable-jupyter),
which bridges the gap between [Observable notebooks](http://observablehq.com) (100% JavaScript) and Python!

## Observable Plot

Quick and easy charts: [Plot](https://observablehq.com/@observablehq/plot) is built with D3 and powered by 
[Observable](http://observablehq.com).
Try it in Colab: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pbogden/observable-jupyter-demos/blob/master/notebooks/observable_plot.ipynb)

Another new Python plotting package, you ask? No. On the one hand, it's true the Plot is a new, amazing open source 
plotting package by the amazing [Mike Bostock](https://observablehq.com/@mbostock), 
creator of D3.js, among other things.
But it's not a Python plotting package, it's 100% JavaScript.
You can use with Python in Jupyter notebooks (and Colab) because of the remarkable 
[observable-jupyter](https://github.com/thomasballinger/observable-jupyter) Python package.

So it is Python or JavaScript, you ask? In a nutshell: As long as you can serialize your data and options as JSON, 
you can use Observable Plot as easily as if it were a Python package. 
My [Observable notebook](https://observablehq.com/@pbogden/observable-plot-jupyter) exposes the various options 
needed to reproduce the plot types in the original Observable Plot notebook. 
Thanks to observable-jupyter, I can use a different dataset that originated on the Python side and gets
sent to the JavaScript side via the API at Observablehq.com.
