# Sketch Transform

A plugin for [Sketch](http://www.sketchapp.com) that provides transformation
tools that are useful for mocking up basic charts (bar, column, line, _etc._).

# Example Use

Here's how I use these plugins to speed up my workflow when I'm mocking up
basic charts in Sketch.

## Bar Charts

This is how I create a fake column or bar chart that fits in a given size and
aligns to pixel boundaries.

1. Draw a rectangle the size of the entire bar chart
2. Choose Plugins→Transform→Split into grid
3. Set the number of columns to the desired number of bars (or set rows for
horizontal bars). For a continuous domain (_e.g._ for a histogram), leave the
gutter at 0
4. Select all but the first rectangle (so that it remains at the original
height)
5. Choose Plugins→Transform→Resize each
6. For column charts set a negative height (set a negative width for bars)
7. Turn on "Cumulative" (so each bar gets progressively smaller) and
"Randomize" to introduce a little noise into the data
8. Select all of the bars and align to the appropriate baseline

![Making a bar chart](https://github.com/darthmall/sketch-transform/raw/master/img/bar_chart.gif)
