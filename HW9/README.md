## Good plot
 Each subplot clearly shows how different features change the wavelength of the model, labeling regions of particular interests. There is no ambiguity or distraction as to what is being observed in each plot, nor is there a distraction from the central point of the plot (how each parameter affects the model). I also think the annotations on the plot guide the observer in a way that is informative and without distracting from the data. One thing I would change in the linewidth to make it a bit bolder so it is easier to see.
 
 <img src="https://github.com/Ajb2307/DSPS_ABaldelli/blob/main/HW9/good_plot.png" width="500">
 
  https://iopscience.iop.org/article/10.3847/1538-4357/ad71d5 

  

## Bad plot
 This plot  is extremely chaotic looking, there is too much information and is over labeled to the point of distraction. To adequetly assess whats needs to be addressed about this plot I am going discuss each of the metrics we discussed in class.

**ambiguity:** In this plot there is ambiguity as to what the reader should be getting out of the plot. Further more there is ambiguity as to what is plotted on the histogram (note it does not match the data distribution). To remedy these issues I would break this plot into two different plots: one scatter and one histogram. 

**distortion:** The axes of this plot contain a puzzling scale thats seems to change without reason distorting the clusters of data. Further more the high density of points in the top all over lap, not allowing the view to decern how many different points are present. The rainbow color scale has some implicit distortion as the change is not precieved linearly by humans. To remedy these issues I would change the scale to perhaps log or some other scale to best show the data, I would make the scatter points smaller and more transparent, and finally I would change the color map to one that is perceptually uniform. If a uniform scale to properly spread this data cannot be found then maybe it would best be overserved in two different plots looking at the large cluster at the top separately.

Additionally I do not believe the line " $M/R = 3$ " and " $M/R^{1.5}=5$ " should both be represented as straight lines, given the change in power, and the x and y axis. This is blantent distortion that should be fixed.

**distraction:** Unlike my previous plot the multicolor labels here, which contain typos, are more of a distraction than clarifying. They are also overlapping and blend in with the point particularly in the top right. The grey background that is white in some areas is also distracting and makes the grey labels even harder to read. The histogram is also very distracting from the scatter plot and should be moved to a new plot as noted above. For the histogram I would also move the bin count axis from the center to the left or right (or both), as its position interrupts the eye fron seeing the histogram as a whole. I think by removing some labels or show casing them elsewhere ther reader will be able to further understand the plot. In addition the grey background needs to be removed, if they wish to highlight a region that can work, but keeping the backgound mostly white will minimize visual noise. 

 
 <img src="https://github.com/Ajb2307/DSPS_ABaldelli/blob/main/HW9/bad_plot.jpg" width="500">

[ [doi.org/10.1073/pnas.1812905116](https://iopscience.iop.org/article/10.3847/1538-4357/ad71d5)](https://www.pnas.org/doi/full/10.1073/pnas.1812905116)
