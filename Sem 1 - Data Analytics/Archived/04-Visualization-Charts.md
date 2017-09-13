# Hello, beautiful people. Its time for us to understand the commonly used charts for data visualization 

> Don't simply show data, tell a story with the aid of charts

### Here is a quick guide on which [data visualization chart/graph](https://www.tableau.com/learn/whitepapers/which-chart-or-graph-is-right-for-you?signin=4fdace60e342e68967da4b8e0554710a) is right for your data? 

## Pareto Charts

Also known as Pareto distribution diagram, it is a vertical bar graph in which values are plotted in descreasing order of relative frequency from left to right, which helps decision makers to identify the most frequent defects, complaints, or any other factor you can count and categorize. 

![Alt Text](http://cdn.ttgtmedia.com/ITKE/uploads/blogs.dir/67/files/2009/02/pareto_chart_customer-complaints.jpg)
  > Here is a [illustration](http://whatis.techtarget.com/definition/Pareto-chart-Pareto-distribution-diagram) on how Pareto Charts 
    can be used to identify what business issues need attention. 
    Sounds useful? Check out this link which guides you on [_how to create a Pareto Charts_](http://blog.minitab.com/blog/understanding-statistics/when-to-use-a-pareto-chart).


## Scatter Plots

It investigates the relationship between different variables. Scatter Plots are an effective way to give you a sense of trends, concentrations and outliers that will direct you to where you want to focus your investigation efforts further.
![Alt Text](https://cdns.tblsft.com/sites/default/files/figure-8.jpg)  
  > This link provides a good guide on [_when to Use a Scatter Diagram_](http://asq.org/learn-about-quality/cause-analysis-tools/overview/scatter.html). Whereas,
    this link shows you what is the best practices for [designing scatter plots.](https://visage.co/data-visualization-101-scatter-plots/)



## GeoChart 

A Geo Chart is also known as a Geographical Chart because Geo is short for Geographical. The area will be a continent, country, city or region. Using the the Geo Chart we can represent many types of data, like the density of an area, population of an area, the users of a specific language of an area and many more. So the main use of a Geo Chart is to represent an area with its special specification. We can also compare two or more areas of data using Geo Chart. One important property of the Geo Chart that it can never be dragged and dropped from one place to another place in the browser and Geo Chart is never scrollable. There are three types of Geo Charts available.

   1) _Region Geo Chart_ - In the region Geo Chart we represent the entire country or continent with the specific color that you want. look below for an example   
    ![Alt Text](http://csharpcorner.mindcrackerinc.netdna-cdn.com/UploadFile/66489a/google-geo-geographical-chart-in-mvc/Images/reigon%20geo%20chart.png)    
    2) _Markers Geo Chart_ - Since it has the name Markers it shows the marks on the chart for the specific location of area with the dots (.) Those dots are present in the form of circles. Here we make the size and color of the circles as we desire. Look at the given example.    
    ![Alt Text](http://csharpcorner.mindcrackerinc.netdna-cdn.com/UploadFile/66489a/google-geo-geographical-chart-in-mvc/Images/Markers%20geo%20chart.png)    
    3) _Text Geo Chart_ - It is the simplest Geo chat in the Text Geo Chart. We show a label text on the specific location. Please go with the given example.    
    ![Alt Text](http://csharpcorner.mindcrackerinc.netdna-cdn.com/UploadFile/66489a/google-geo-geographical-chart-in-mvc/Images/textgeochart.png)     
    _Note that the geochart is not scrollable or draggable, and it's a line drawing rather than a terrain map_
    


## Box Plot 

The box plot is a standardized way of displaying the distribution of data based on the five number summary: minimum, first quartile, median, third quartile, and maximum.
The lines extending parallel from the boxes are known as the "whiskers", which are used to indicate variability outside the upper and lower quartiles. Outliers are sometimes plotted as individual dots that are in-line with whiskers. Box Plots can be drawn either vertically or horizontally.

Typically used in descriptive statistics, Box Plots are a great way to quickly examine one or more data sets graphically. Although they may seem primitive in comparison to a Histogram or Density Plot, they have the advantage of taking up less space, which is useful when comparing distributions between many groups or data sets.

![Alt Text](http://www.datavizcatalogue.com/methods/images/anatomy/box_plot.png)

Here are the types of observations we can make from viewing a Box Plot

    1) What the key values are, such as: the average, median 25th percentile etc.
    
    2) If there are any outliers and what their values are.
    
    3) Is the data symmetrical.
    
    4) How tightly is the data grouped.
    
    5) If the data is skewed and if so, in what direction.
    


## Histogram

A Histogram visualises the distribution of data over a continuous interval or certain time period. Each bar in a histogram represents the tabulated frequency at each interval/bin. The total area of the histogram is equal to the number of data.

Histograms help give an estimate as to where values are concentrated, what the extremes are and whether there are any gaps or unusual values. They are also useful for giving a rough view of probability distribution.

![Alt Text](http://www.datavizcatalogue.com/methods/images/anatomy/histogram.png)

 While the box plot hides variation in between the values that it does show, a histogram can provide more details. Histograms look like bar charts, but they are not the same. The horizontal axis on a histogram is continuous, whereas bar charts can have space in between categories.
 
 
## Density Plot

 A Density Plot visualises the distribution of data over a continuous interval or time period. This chart is a variation of a Histogram that uses kernel smoothing to plot values, allowing for smoother distributions by smoothing out the noise. The peaks of a Density Plot help display where values are concentrated over the interval.

![Alt Text](http://www.datavizcatalogue.com/methods/images/anatomy/SVG/density_plot.svg)

An advantage Density Plots have over Histograms is that they're better at determining the distribution shape because they're not affected by the number of bins used (each bar used in a typical histogram). A Histogram comprising of only 4 bins wouldn't produce a distinguishable enough shape of distribution as a 20-bin Histogram would. However, with Density plots this isn't an issue.


## Bar Chart

The bar chart is a chart with rectangular columns proportional in length to the values they represent. Simply put, longer bars equal bigger numbers. On one axis these bars compare categories, while on the other they represent a discrete value. 

![Alt Text](http://www.datavizcatalogue.com/methods/images/anatomy/bar_chart.png)

When to Use?
Bar charts are used to showcase discrete data—that’s data that is based on counts and can only be certain values. They are most effectively to:

    1)Show change over time (e.g., the net monthly earnings of Tesla Motors in a year)
    
    2)Compare values of different categories (e.g., a year’s fishing yields for different species of fish)
    
    3)Compare parts of a whole (e.g., the percent distribution of Netflix rentals across genres)
    
Bars Charts are distinguished from Histograms, as they do not display continuous developments over an interval. Bar Chart's discrete data is categorical data and therefore answers the question of "how many?" In each category.

One major flaw with bar charts is labeling becomes problematic when there is a large number of bars. Like in the graph below the labels would have made it complex.

![Alt Text](http://www.datavizcatalogue.com/methods/images/top_images/bar_chart.png)

While making a bar chart always start y-axis at 0 whenever possible, if not it truncates the data and dosent actually reflect the real data.
![Alt Text](https://visage.co/wp-content/uploads/2014/12/Screen-Shot-2014-12-08-at-5.57.51-PM.png)

## Columnn Chart 

Column charts are the most widely used charts for consuming quantitative information based on a single dimension (products, employees, regions, etc) with one or multiple like-measures (sales, costs, etc). Both bar and column charts are extremely effective for representing quantitative information using the relative bar size against a common axis and scale to provide powerful comparative analysis. you can use it as a categorical bar graph where two or more stuffs can be compared for a given category. Look at the example below:

![Alt Text](https://multimedia.journalism.berkeley.edu/media/upload/tutorials/dataviz-basics/groupbar.png)


## Line Chart 
Line Graphs are used to display quantitative value over a continuous interval or time span. It is most frequently used to show trends and relationships (when grouped with other lines). Line Graphs also help to give a "big picture" over an interval, to see how it has developed over that period.

We can use it when we have a continuous dataset. If seeing the trend of your data is the goal, then this is the chart to use. Line charts show time-series relationships using continuous data (that which is measured and has a value within a range). They allow a quick assessment of acceleration (lines curving upward), deceleration (lines curving downward), and volatility (up/down frequency). They are excellent for tracking multiple data sets on the same chart to see any correlation in trends.

Line Graphs are drawn by first plotting data points on a Cartesian coordinate grid, then connecting a line between these points. Typically, the y-axis has a quantitative value, while the x-axis has either a category or sequenced scale. Negative values can be displayed below the x-axis.

![Alt Text](http://www.datavizcatalogue.com/methods/images/anatomy/line_graph.png)


## Combination Chart
The combination chart is a visualization that combines the features of the bar chart and the line chart. The combination chart displays the data using a number of bars and/or lines, each of which represent a particular category. A combination of bars and lines in the same visualization can be useful when comparing values in different categories, since the combination gives a clear view of which category is higher or lower. An example of this can be seen when using the combination chart to compare the projected sales with the actual sales for different time periods like in example below which potrays the data beautifully by combining stacked column charts and line chart.

![Alt Text](https://dpspowerbi.blob.core.windows.net/powerbi-prod-media/powerbi.microsoft.com/en-us/documentation/articles/powerbi-service-tutorial-combo-chart-merge-visualizations/20170517043955/power-bi-titles-on.png)

## Area Chart
Area charts depict a time-series relationship, but they are different than line charts in that they can represent volume. Thus we can use it to show trends of several related stuffs in a given period of time. Information in an area chart is plotted on the x- and y-axis; data values are plotted using data points that are connected using line segments. Area charts are primarily used when the magnitude of the trend is to be communicated (rather than individual data values). To showcase this magnitude, the area between the line segments and the axes is highlighted by filling it with color. 

![Alt Text](http://www.datavizcatalogue.com/methods/images/anatomy/area_graph.png)

We do not use area chart to potray fluctuating data like price of shares,etc.

Another variant of area chart is __Stacked Area Chart__ which is used to show changes in composition over time. A good example would be the changes of market share among top players or revenue shares by product line over a period of time.

![Alt Text](https://eazybi.com/static/img/blog_page/posts/2016_03_01/data_visualization_stacked_area_charts.png)

Stacked area charts might be colorful and fun, but you should use them with caution, because they can quickly become a mess. Don’t use them if you need an exact comparison and don’t stack together more than three to five categories. 
 


## Word Trees

By the end of this section, you should have accomplished the following:

- [ ] What are word trees for?
- [ ] Explain how word trees work

A word tree is a visualization tool that helps you spot which words often follow or precede another word.

It is used to visualize political transcripts, bible and etc. Let's say if you wish to analyze a text-heavy dataset and want to preserve the structure, a word tree would be an approach you could take. In the case of political transcripts, what words came before and after another word would matter. It gives context of the situation.

Refer to the image below

![Word Trees on Imgur](http://i.imgur.com/nvpsvLg.png)

We could infer that the word "nation" might be commonly associated with the following words/concepts/phrases:
- liberty
- dedicated
- conceived
- God
- live

This could mean that a nation can only be conceived with the liberty and dedication of its people. What's also interesting is the use of the word, God. This could mean that at the point of writing, the author was expressing what was ideal (a concept associated with the notion of God)

Clearly, the use of word trees presents interesting opportunities to explore textual data in a richer manner.

## Timelines

Let's say you're given the task of analyzing all the events that happened from 1900s till today's date. One of the easiest ways to do that would be to use a Timeline. Or say you're a business man and wanted to explore the history of failing enterprises so as to glean some valuable lessons.

![Nokia's Downfall Timeline](http://i.imgur.com/jGZc4EO.png)

- [ ] I have checked out [Nokia's Downfall Timeline](https://www.engadget.com/2016/04/22/microsoft-mobile-timeline/)
- [ ] I know how Timelines help me to visualize events more effectively now
- [ ] I know now that timelines aren't that hard to do :P

## Bubble Chart
A bubble chart is a visualization that is good for displaying nominal comparisons or ranking relationships. This is a scatter plot with bubbles, best used to display an additional variable. 

Bubble Chart:
![Alt Text](https://hlhaylac2v-flywheel.netdna-ssl.com/wp-content/uploads/2015/02/Screen-Shot-2015-02-04-at-4.41.48-PM.png)

Bubble Map:
x and y values are effectively latitude and longitude coordinates representing a geographic location.
![Alt Text](https://hlhaylac2v-flywheel.netdna-ssl.com/wp-content/uploads/2015/02/Screen-Shot-2015-02-04-at-4.43.10-PM.png) 


Best Practices for bubble chart:
1. Make sure the labels are visible. 
All labels should be unobstructed and easily identified with the corresponding bubble.
![Alt Text](https://hlhaylac2v-flywheel.netdna-ssl.com/wp-content/uploads/2015/02/Screen-Shot-2015-02-04-at-4.49.52-PM.png) 

2. Size Bubbles Appropriately. 
Bubbles should be scaled according to area, not diameter.
![Alt Text](https://hlhaylac2v-flywheel.netdna-ssl.com/wp-content/uploads/2015/02/Screen-Shot-2015-02-04-at-4.50.54-PM.png)

3. Don't Use Odd Shapes. 
Avoid adding too much detail or using shapes that are not entirely circular, this can lead to inaccuracies.
![Alt Text](https://hlhaylac2v-flywheel.netdna-ssl.com/wp-content/uploads/2015/02/Screen-Shot-2015-02-04-at-4.51.30-PM.png) 

## Pie Chart and Donut Chart
Pie charts is one of the popular charts. They are used for making part-to-whole relationship or comparisons with discrete or continuous data. Pie charts and  donut charts are functionally similar charts for showing parts of a whole. The following charts display the same information.

![Alt_Text](https://help.gooddata.com/download/attachments/26082902/Donut%20vs%20pie%20chart.jpg?version=2&modificationDate=1430256082687&api=v2)

## Waterfall Chart
Waterfall charts is a visualisation that shows the net change in some amount between a starting point and end point. The net change is typically displayed as though broken down into components.
For example, the waterfall chart below displays the net change in a sales pipeline during a given quarter. The first bar represents the starting point (total opportunity amount at the start of the quarter), while last bar represents the end point (total opportunity amount left at the end of the quarter).
Together, the two central bars in red represent the difference between the start point and end point.
Unlike a typical bar chart, this waterfall chart actually displays four metrics, rather than a single metric broken down by one or more attributes.
![Alt_Text](https://help.gooddata.com/download/attachments/26083197/Waterfall%20chart.jpg?version=2&modificationDate=1430257957724&api=v2)

## Treemap Chart
A treemap chart provides a hierarchical view of your data and makes it easy to spot patterns, such as which items are a shop's best sellers. The tree branches are represented by rectangles and each sub-branch is shown as a smaller rectangle. A leaf node's rectangle has an area proportional to a specified dimension of the data. Often the leaf nodes are colored to show a separate dimension of the data.

When the color and size dimensions are correlated in some way with the tree structure, one can often easily see patterns that would be difficult to spot in other ways, such as if a certain color is particularly relevant. Another advantage of treemap is they make efficient use of space. As a result, they can display thousands of items on the screen simultaneously.

Below is a treemap of soft drink preference in a small group of people. Color and gradients are used to group items, while still identifying individual items.

![Alt_Text](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/Gradient_grouped_treemap.jpg/600px-Gradient_grouped_treemap.jpg)

## Gantt Chart
A gantt chart is a visualization to present transactions or sessions on different resources over a period of time. The data will be split vertically into different categories (the resources), and will be colored according to the series. 

Below is a gantt of usage of tape drives over a period of time. 
![Alt_Text](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/000/203/356/datas/gallery.jpg) 

## Organisational Chart
An organizational chart is a visualization that shows the structure of an organization and the relationships and relative ranks of its parts and positions/jobs. 

![Alt_Text](https://public.tableau.com/static/images/Du/DunderMifflin/DunderMifflinOrgChart/1.png) 

Generating organisational charts using data is quite uncommon. Read on [How to create organisational chart with Tableau](https://smithna.github.io/tableau-org-chart/)

## Candlestick Chart
Candlestick chart is a visualization that is used as a trading tool to visualise and analyse the price movements over time for securities, derivatives, currencies, stocks, bonds, commodities, etc. Although the symbols used in Candlestick Charts resemble a Box Plot, they function differently. 

Candlestick Charts display multiple bits of price information such as the open price, close price, highest price and lowest price through the use of candlestick-like symbols, that each represent the compressed trading activity for a single time period (a minute, hour, day, month, etc). Each Candlestick symbol is plotted along a time scale on the x-axis, to show the trading activity over time.

Candlestick Charts are great for detecting and predicting market trends over time and are useful for interpreting the day-to-day sentiment of the market, through each candlestick symbol's colouring and shape. For example, the longer the body is, the more intense the selling or buying pressure is. While, a very short body, would indicate that there is very little price movement in that time period and represents consolidation.

![Alt_Text](http://www.datavizcatalogue.com/methods/images/top_images/SVG/candlestick_chart.svg) 

[More Detailed Explanation of Candlestick Chart](http://www.datavizcatalogue.com/methods/candlestick_chart.html) 


## Steam and Leaf Plot
Stem & Leaf Plots are a way of organising data via their place value to show the distribution of data. Place values are shown ascending downwards on a "stem" column. Data that is within each place value is listed and extends sideways from it as a "leaf".

Stem & Leaf Plots are useful for highlighting outliers and finding the mode. However, Stem & Leaf Plots are limited in the size of dataset they can handle. If the data set is too little and they become pointless, too much and the chart becomes over-cluttered.

![Alt_Text](http://www.datavizcatalogue.com/methods/images/top_images/SVG/stem_and_leaf_plot.svg) 

## Multi-Vari Chart
Multi-vari charts are a way of presenting analysis of variance data in a graphical form, providing a "visual" alternative to analysis of variance.

They can help you to study and find patterns of variation from many possible causes on a single chart. They can also be used to study variations within a subgroup or between subgroups and etc. 

The multi-vari chart below displays differences between the two call centers (Montpellier and Saint-Quentin: red points on the graph), the weekdays (green points on the graph) and the day hours (several black and white symbols). It suggests that waiting times are longer on Mondays (Mon: in the first part of the graph).

![Alt_Text](http://cdn2.content.compendiumblog.com/uploads/user/458939f4-fe08-4dbc-b271-efca0f5a2682/31b80fb2-db66-4edf-a753-74d4c9804ab8/Image/66c1fb49e1432b95628ea53d53ca030a/multi_vari_chart_for_duration_by_hour___day_1.jpg) 

[More Examples of Multi-Vari Chart](http://blog.minitab.com/blog/applying-statistics-in-quality-projects/using-multi-vari-charts-to-analyze-families-of-variations)



## QQ Plot














_Further Readings_

 > If you want to further look into charts and data visualization you can take a look at the following which happens to be a pretty good guide for data visualization and some of the charts mentioned above: [Complete guide to data visualization](https://cdn2.hubspot.net/hub/53/file-863940581-pdf/Data_Visualization_101_How_to_Design_Charts_and_Graphs.pdf)
 
 > A great blog which provides a wide range of data visualisation with detailed explanation : [Data Visualisation Catalogue](http://www.datavizcatalogue.com/index.html) 
