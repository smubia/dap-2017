# Selecting the Correct Charts


# Welcome my fellow mates, 
### Lets see how to choose the right chart for the visualisation of our analysis

One of the most common issues when creating a visualization is not understanding the best ways to display the data.

We must ask an important question :

__What do we want to show?__
- [ ] Comparison 
- [ ] Composition
- [ ] Distribution
- [ ] Relationship

### Comparison

Comparison charts are and should be used to compare the magnitude of values to each other and can be used to easily
find the lowest and highest values in the data. It can also be used to compare current values versus old
to see if the values are increasing or decreasing. 
Common questions are :
* “what products sells best? ”
* “how are our sales compared to last year? ”

We can compare:

**1) Among items**

* One Variable per Item 
  * Many Categories - ___Table or tables with embeded charts___
  * Few Categories - ___Bar Charts___

* Two Variable per Item - ___Variable width chart___ ( or bar Mekko chart, is a bar chart where column widths are scaled such that the total width matches the desired chart width and there are no gaps between columns. A good use case for this type of chart is for tracking growth against actual size for categorical data. For example, sales growth for a certain product line will be the column height and the total sales value for that product line will be the column width allowing us to easily spot which products lines are growing and what is their impact on our total sales activity. look the example below)

  ![Alt Text](http://www.andypope.info/charts/colwidth2.GIF)


**2) Over time**

* Many Periods - ___Circular area chart___ Like in the figure below chemical concentration over different months can be easily compared while the area part shows composition of it being absorped in each given time.

  ![Alt Teext](http://2.bp.blogspot.com/-V8hUbjmkM1Y/VQi7j2GViLI/AAAAAAAAAPk/vQZMif_Yvhg/s1600/circular_area.png)

Now if we use line graph for the same concept but over a period of 10 years where the number of months would be 120. Imagine how messy the graph would look. Thus we should use circular area chart in comparison over time where many periods are involved

* Few Periods 

  * Few categories - ___Bar chart___ 
  
  ![Alt Text](http://www.onlinemathlearning.com/image-files/bar-charts-1.gif)
  
  * Many Categories - ___Line Chart___
  
  ![Alt Text](https://docs.oracle.com/javase/8/javafx/user-interface-tutorial/img/line-order.png)



### Composition

Composition charts are used to see how a part compares to the whole and how a total value can be
divided into shares. A composition charts shows the relative value, but some charts can also be used
to show the absolute difference. The difference is between looking at percentage of total and value
of total. 
Commons questions are:
* “how big part of the market do we have in a region” 
* “what areas is our budget divided into”.

We can compare:

**1) Changing over Time**
  
  * When only relative difference matters : ___Stacked 100% area or bar chart___ Like in the image below we can easily see the relative composition of sales by different brands changing over a period of time
  
  ![Alt Text](https://eazybi.com/static/img/blog_page/posts/2016_03_01/data_visualization_stacked_area_charts.png)
  
  * When relative and absolute difference matters : ___Stacked area or bar chart___ As soon as we see the image below we get to see absolute sales and also are able to infer the relative difference in sales of each product between time periods.
  
  ![Alt Text](https://docs.oracle.com/cd/E39271_01/studio.300/studio_users/images/chart_example_stacked_bar.png)
  
**2) Static**
  
  * Simple share of total : ___Pie Chart___ the figure below easily tells us the part of the total, which is concerned.
  
  ![Alt Text](https://visage.co/wp-content/uploads/2014/10/BigData_NewsRoom-816x612.png)
  
  * Accumulation or subtraction to total : ___Waterfall Chart___ the composition of each accumulates to the total vertical bar in the image below, making it easier to understand.
  
  ![Alt Text](http://cdn.business2community.com/wp-content/uploads/2014/07/Waterfall_Chart-600x338.png)
  
  * Accumulation total & absolute difference matters : ___Tree Map___ In the image tree map helps us understand the accumulated total of oil consumption and also the difference.
  
  ![Alt Text](https://www.kaushik.net/avinash/wp-content/uploads/2014/11/oil_consumption_treemap.png)
  
  
### Distribution

Distribution charts are used to see how quantitative values are distributed along an axis from lowest to
highest. Looking at the shape of the data a user can identify characteristics such as the range of
values, central tendency, shape and outliers.
It can be used to answer questions such as:
* “number of customers per age group” 
* “how many days late are our payments”

**1) Single Variable** - ___Bar Histogram___
  
  ![Alt Text](http://libweb.surrey.ac.uk/library/skills/Number%20Skills%20Leicester/images/pic033.gif)  




### Relationship Visualizations

Relationship charts are used to see the relationship between the data and can be used to find
correlations, outliers and clusters of data.
Common questions are :
* “is there a correlation between advertising spend and sales for our products” 
* “how does expenses and income vary per region and what’s the deviation”

 ___Scatter Plot___

![Alt Text](http://seaborn.pydata.org/_images/categorical_15_0.png)

  
  

Now that you have completed this section, we hope you can easily choose the perfect graph for your visuals! :smile:



## Next Section
Once you've understood the key concepts introduced in this section, proceed on to the next section, the [Mini-Project](/exploratory-data-analytics-py/1-analytics-basics/mini-project.md) for Analytics Basics.