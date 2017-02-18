
Assignment 4 - Visualizations and Multiple Views  
===

Link- https://rohitpalsingh7.github.io/04-MapsAndViews/index.html


Teams-Rohitpal Singh,Jui saba guram
---



Resources
---
https://bl.ocks.org/mbostock/5872848

https://github.com/square/crossfilter/wiki/API-Reference

Data
---
http://donnees.ville.montreal.qc.ca/dataset/velos-comptage
We took the dataset from this site.It contains the data about the no of cycles run in different streets for different months of the year 2012.



![alt_tag](https://github.com/jguram/04-MapsAndViews/blob/master/Screen%20Shot%202017-02-15%20at%2011.20.24%20PM.png)



Here we have visualized the data about the no of cycles run in Montreal in the year of 2016.

The first pie chart represents the different months and they are sliced according to the percentage of the cycles run in that particular month.

When you select a particular month,the second chart represents which streets were used in that particular month and are sliced according to the % of cycles ran in that month.

The Final bar chart represents the no of cycles ran in those streets for the particular month.





Technical Acheivements
---
Use of Dispatcher(event handler) to handle multiple coordinated views.

Use of crossfilter to process the data and parse it.

Design acheivements
---
Legends for first graph explains % of cycle in sorting order (descending) so user can easily identify which month has high number of cycle .

Visual encoding hue to categories the month, streets . Also second graph and third graph represents streets so they are encoded with same color.

