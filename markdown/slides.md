Introduction
---------------



Why visualize data
---------------------------------
<div class="flex-row">
  <div style="text-align:center">
    <div> Exploration </div>
    <img width="400px" src="images/example_exploration.svg">
    <ul>
      <li> High information density </li>
      <li> Little effort in creation </li>
    </ul>
  </div>
  <div style="text-align:center">
    <div> Presentation </div>
    <img width="400px"  src="images/example_presentation.svg">
    <ul>
      <li> Low information density </li>
      <li> Lots of effort in creation </li>
    </ul>    
  </div>
</div>


What is (not) a *good* plot
--------------------------
<div style="text-align:center">
<img width="50%" src="https://serialmentor.com/dataviz/introduction_files/figure-html/ugly-bad-wrong-examples-1.png">
  <div style="font-size: .5em; text-align: center; margin-bottom: 20px">
  Image from Fundamentals of Data Visualization by Claus O. Wilke
  </div>
</div>


How to get from exploration to presentation?
--------------------------------------------------
1. Make a *good* exploratory plot
  * Next steps are just refinements
2. Define message of the plot
  * What information should be in the plot?
  * What information should be highlighted?
  * What information can be left out?
3. Define presentation medium
  * What elements are suitable?
  * How long will the audience be looking at the plot?



Tools - plot types
-----------------------------


Tools - plot types - finding the right type
-----------------------------------------------
* 2019 stack survey data on salaries for male/female respondents.
* ~45000 respondents, > 90% male

<div class="fragment">
  <img src="images/stack_plot1.svg">
  <div>Does this plot give a representative image?</div>
</div>


Tools - plot types - finding the right type
-----------------------------------------------
Show the distribution in more detail
<div>
  <img class="fragment" width="450px" src="images/stack_plot2.svg">
  <img class="fragment" width="450px" src="images/stack_plot3.svg">
</div>



Tools - plot elements
-------------------------------
<div>
<img src="https://serialmentor.com/dataviz/aesthetic_mapping_files/figure-html/common-aesthetics-1.png">
<div>Image from [Fundamentals of Data Visualization by Claus O. Wilke](https://serialmentor.com/dataviz/)</div>
</div>



Tools - colors
------------------------
* Choosing a colormap:
  * Represent values: sequential
  * Distinguish lines: qualitative
  *
https://matplotlib.org/3.1.0/tutorials/colors/colormaps.html



Aims of this workshop
-------------------------------
* Basic plotting with `matplotlib`
* Utilize `seaborn` to improve your plots
* Utilize `pandas` together with `seaborn`


Matplotlib
----------------
* Designed to work well with *scipy ecosystem*
* Choice between object oriented and procedural interface


Seaborn
---------------
* High-level interface for drawing attractive and informative statistical graphics.
* Build upon matplotlib making visualization fully adapteble.
* Designed to work together with pandas DataFrames



Resources
---------------
* [Fundamentals of Data Visualization by Claus O. Wilke](https://serialmentor.com/dataviz/)
* [Data to Viz](https://www.data-to-viz.com/index.html)
* [Python Graph Gallery](https://python-graph-gallery.com)
