---
layout: page
title: Getting started
subtitle: #Some examples of jag usage
---

## Data sources

At the moment *jag* supports data source in [CSV format](https://en.wikipedia.org/wiki/Comma-separated_values) and data in simple table format. Examples of such files you can find in [jag repository](https://github.com/seleznevae/jag/tree/master/tlmExamples). Feel free to use them during getting familiar with **jag**.

## Loading data sources

There are 2 main means to load your data source:
1. Use menu **_Data/Load data source_**
<img src="../img/getting-started/loading-data-source-1.gif" style="width:100%;" alt="Load data source gif" />

2. Use drag and drop 
<img src="../img/getting-started/loading-data-source-2.gif" style="width:100%;" alt="Load data source gif" />

During loading usually the dialog with available data source is shown. In this dialog it is possible to delete a data source, set a particular style for the plots from this data source, set some filters for the data, etc.



## Creating simple plots

To create a new plot use the menu item **_Plot/New plot_** or the button on the top left side of the main window.

After that a menu shown where you can choose data you would like to draw. To choose a parameter just click on it. 

<img src="../img/getting-started/create-simple-graph.gif" style="width:100%;" alt="Create simple graph gif" />

By default all parameter will be considered by **jag** as functions of some independent argument (usually it is time or something like that). If you don't want to draw function _parameter1 = f(argument)_ but want to draw function _parameter1 = f(parameter2)_ use the left button of the mouser to choose _parameter1_ and the right button to choose _parameter2_ as an argument.

## Plot layouts

Layout control is usually done by drag and drop.

<img src="../img/getting-started/moving-graphs.gif" style="width:100%;" alt="Moving graphs gif" />

<img src="../img/getting-started/layout-changing.gif" style="width:100%;" alt="Layout changing gif" />



## Modes

Jag main window can be in several modes (switch from one mode to another is usually achieved by using buttons in the toolbar):

1. **Normal mode** 
In this mode you can move graphs from one axis to another

2. **Measuring mode** 
In this mode you can explore data values. Current values of all graphs are shown at the bottom of the main window. If you move mouse with the left button pressed it is possible to measure distance between 2 particular points.
<img src="../img/getting-started/measuring-mode.gif" style="width:100%;" alt="Measuring mode gif" />

3. **Level drawing mode** 
In this mode it possible to mark some events with vertical line (left button click) and levels with horizontal line (right button click).

4. **Remark drawing mode**

5. **Zoom x mode**

6. **Zoom y mode**

7. **Zoom xy mode**

8. **Motion mode**

9. **Fast secondary processing mode**

## Secondary processing

You can calculate basic mathematical functions based on the graphs currently presented on the plot.

<img src="../img/getting-started/secondary-processing.gif" style="width:100%;" alt="Secondary processing gif" />

In secondary processing dialog each graph is aliased as **g1, g2, ... gn**. So, for example, to get the sum of the first and the third graphs put **g1 + g3** to the function editing widget at the bottom of the secondary processing dialog.

At the moment a lot of base mathematical functions along with some signal processing functions are available.
