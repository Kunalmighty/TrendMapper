![TrendMapper Logo](https://github.com/Kunalmighty/TrendMapper/blob/master/TrendMapper%20slide%20logo.png)

DISCLAIMER: The Bokeh map visualizations implemented in this project are not viewable on Github. In order to view the visualizations, please download the Jupyter notebook file, and run the notebook on your machine. 

Current data maps show discrete data points, not how the data changed over time. 
The TrendMapper project develops new data visualization techniques to show trends of change in data values, rather than single data points.

In particular, we will focus on trends for which spatial information is available.

![TrendMapper How](https://github.com/Kunalmighty/TrendMapper/blob/master/TrendMapper%20slide%20how.png)

PCA dimensionality reduction means: the information along the least important principal axis or axes is removed, leaving only the component(s) of the data with the highest variance. The fraction of variance that is cut out (proportional to the spread of points about the line formed in Figure 5-83) is roughly a measure of how much “information” is discarded in this reduction of dimensionality. 

![TrendMapper How 2](https://github.com/Kunalmighty/TrendMapper/blob/master/TrendMapper%20slide%20how%202.png)

The first dataset that I have worked with is a history of temperature data for 36 cities in the United States. 
This dataset includes hourly temperature readings for a period of 5 years. This is what the graph for this data looks like. 
As you can see, there is a lot of information in a graph like this, which makes it difficult to tell which cities have precisely similar trends in temperature change. This is where Principal Component Analysis will help us smoothen out these curves while retaining the most important information in the curves. 
Here you can see results of the PCA analysis conducted on this dataset. These results will then be accumulated and plotted on a map of the US using a Python web framework called Bokeh and the result will look something like this.  

![TrendMapper Results](https://github.com/Kunalmighty/TrendMapper/blob/master/TrendMapper%20slide%204%20results.png)

