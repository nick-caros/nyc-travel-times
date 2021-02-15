# NYC Node-to-Node Travel Times

This is code I used in my blog post on calculating time-dependend travel times between every intersection in Manhattan, New York. The main code in Jupyter Notebook format is saved in `NYC Travel Times.ipynb`. The code requires Python 3.7, [Shapely](https://github.com/Toblerity/Shapely), [pyproj](https://github.com/jswhit/pyproj), [Pandas](http://pandas.pydata.org/), [Numpy](http://www.numpy.org/), [NetworkX](https://networkx.org/), [OSMnx](https://github.com/gboeing/osmnx), and of course [Jupyter Notebook](http://jupyter.org/).

This analysis involves combining two different sources of data: the New York City road network from [OpenStreetMap](https://www.openstreetmap.org/copyright) and link level travel speeds from [Uber Movement](https://movement.uber.com/?lang=en-US). OpenStreetMap data are © OpenStreetMap contributors. 

A full description of this work, the motivation behind it and the possible use cases is provided [here]().
