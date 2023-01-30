Here are two highlighted programs from my Summer Research Project held in the Faculty of Mathematics at Cambridge.

## "timeSeriesHeatMap.py"
 - The file named "timeSeriesHeatMap.py" may require the installation of a few (common) packages, which may be installed using pip. These include pygame, requests and imageio.
 - This file takes time-series data from a URL, unzips it (it's packaged with the bz2 protocol on the website), and uses Pygame to render it. This makes a simulation of what the electrode array "sees" when it is placed in the petri dish of neurons.
 - It also screenshots each frame and collates into an mp4 file, called x-y-z.mp4, where x is the plating number, y is the channel number and z is the day number. This makes it easy to share and discuss any interesting events.
 - This was crucial in really being able to "see" the data before diving into the analysis.

## "timeIntervalCV.py"
- The file named "timeIntervalCV.py" may require installation of matplotlib.
- It plots a boxplot of the coefficient of variance of the data across different days.
- In this file I experimented with data treatment, and what the boxplots would look like if I ignored data with less than n datapoints, or weighted data by the amount of datapoints available. 
- The file takes about 200 seconds to run.
