# Data-visualization-with-python

from bokeh.plotting import figure, output_file, show 

output_file("scatter.jpg")

p=figure()

p.circle([1,2,3,4,5],[4,7,1,6,3], color="navy")

show(p)
