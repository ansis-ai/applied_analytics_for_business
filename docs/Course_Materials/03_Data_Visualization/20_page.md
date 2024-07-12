---
title: Basic Chart Types and Graphs
author: [Wilson Loh]
date: 2022-05-01
---


## What Makes a Chart Effective?

Data visualization is a blend of creativity and scientific principles. In the realm of creativity, there are no fixed rules for visualization; numerous methods exist for presenting data. However, when dealing with facts, figures, and measurements, a structured approach enhances understanding and effectiveness.

<br>
For those new to data visualization, selecting the most suitable chart type can be challenging. Many individuals learn by emulating others' work without grasping the underlying rationale, resulting in a lack of theoretical understanding.

<br>
Therefore, prior to embarking on data visualization, it is essential to consider the following:

- **Determine the Purpose** (_Kosara 2016_) - (Analytical or Presentational): Understanding why you are creating a visualization is crucial. Visualizations can serve various purposes, such as exploring and analysing data to enable viewers to discover insights on their own or presenting findings to raise awareness or make decisions. For instance, a journalist creating a weather report visualization aims to present key trends and inform the general public, while climate scientists use visualizations to convey their findings to policymakers regarding climate change action.
- **Identify Your Audience** (_Mekhatria 2017_): After clarifying the purpose, it's vital to know who the intended audience is. Regardless of the target audience, customization to their specific needs, interests, expertise, and analytical abilities is essential. Cultural preferences, expertise levels, and other factors, like colour symbolism in different cultures, play a significant role in designing an effective visualization. For example, in Chinese culture, red represents dynamism or positivity, whereas in much of the Western world, blue or green symbolizes positive trends, such as sales revenue. A visualization created for a finance analyst will differ from one designed for a marketing manager, highlighting the importance of customization for effectiveness.
- **Choose the Right Chart Type** (_Mekhatria 2017_): Once the purpose and audience are determined, selecting the appropriate chart type is crucial. This ensures that the visualization resonates with the audience and empowers them to explore data, uncover insights, and make decisions based on different scenarios.

By addressing these questions, you can develop a clearer vision of the ideal chart for your data. A simplified guideline for using various chart types includes using line charts to track trends over time, bar charts for quantity comparisons, scatter plots for assessing the relationship between two data variables, bubble charts to depict the interaction of three data variables, and pie charts for comparing parts within a whole. However, let's delve further into various presentation styles and common chart types.

## Basic Chart Type and Graphs

Charts play a vital role in the realm of data analysis, offering a means to distil vast data sets into easily comprehensible formats. Visual representations of data not only unearth insights for newcomers to the data but also effectively communicate discoveries to those who may not have access to the raw data. The vast array of available chart types each serves distinct purposes, and often, the greatest challenge in crafting a data visualization lies in selecting the most suitable chart type for the specific task at hand.

<br>
The choice of the appropriate chart type hinges on several factors. Consideration should be given to the nature of the metrics, attributes, or variables slated for representation. Additionally, the intended audience plays a pivotal role – is the visualization primarily for personal exploration or destined for a broader viewership? Finally, the desired message that you wish the audience to glean from the visualization should guide your selection (Mike YiMary Sapountzis, 2019).

- **Bar Chart:** A bar chart employs bars to represent values, with each bar aligning with a specific category or group. These charts can be oriented either vertically or horizontally, with vertical ones often referred to as column charts. Opting for a horizontal bar chart is advantageous when dealing with numerous bars to visualize, or when labels necessitate extra space for clarity.
- **Line Chart:** Line charts depict fluctuations in values along continuous measurements, particularly when data is tracked over time. The upward or downward movement of the line highlights positive and negative shifts, revealing overarching trends that assist readers in making predictions or future projections. Additionally, multiple line charts can lead to the creation of related charts like sparklines or ridgeline plots.
- **Scatter Plot:** A scatter plot represents values on two numerical variables through points placed on two separate axes, each dedicated to one variable. Scatter plots offer a flexible means of illustrating the connection between these variables, whether the correlation is robust or weak, positive or negative, linear or nonlinear. They are also valuable tools for pinpointing outlier points and detecting potential data gaps.
- **Box Plot:** A box plot employs boxes and whiskers to provide a concise summary of value distribution within distinct measured groups. The positioning of the box and the ends of the whiskers indicates the central areas where the bulk of the data is concentrated. Box plots are frequently utilized when there are multiple groups for comparative analysis, while other charts with greater detail are favoured when dealing with a single group for representation.
- **Histogram:** When the groups represented in a bar chart involve continuous numeric ranges, it's possible to condense the bars to create a histogram. In histograms, the lengths of the bars usually represent the frequency counts of data points, and their configurations reveal the distribution of variables within your data. However, if the vertical value doesn't represent a frequency count, a different chart type, such as a line chart, is typically chosen.
- **Stacked Bar Chart:** A variation of the typical bar chart involves splitting each bar into several smaller bars according to values from a secondary grouping variable, known as a stacked bar chart. This approach enables you to not only assess the primary group values, as you would in a standard bar chart, but also visually represent the proportionate breakdown of each group's entirety into its individual components.
- **Area Chart:** An area chart shares a common basis with a line chart, featuring interconnected value points with line segments. However, it introduces an element from the bar chart, incorporating shading between the line and a baseline. This type of chart is frequently utilized in conjunction with stacking, effectively illustrating changes not only in the overall total over time but also in the contributions of its individual components.
- **Bubble Chart:** An alternative method for illustrating the connection between three variables involves adapting a scatter plot. If the third variable is categorical, various shapes or colours can be employed to denote group affiliation among the data points. If there's an inherent order to the data points, they can also be linked with line segments to depict the sequence of values. When the third variable is numerical, this is where the bubble chart becomes relevant. A bubble chart extends the fundamental scatter plot by using the value of the third variable to determine the size of each data point.
- **Heat Map:** The heatmap displays a grid of data points derived from two variables under consideration. These axis variables can take on numerical or categorical forms, and the grid is formed by dividing each variable into intervals or categories, similar to how a histogram or bar chart is constructed. The cells within this grid are coloured according to their values, typically with darker shades indicating higher values. When there's a substantial number of data points to represent, but their density makes it challenging to discern the genuine relationship between variables, a heatmap offers an intriguing alternative to a scatter plot.
- **Pie Chart:** Pie charts are used widespread. However, pie charts employ an unconventional representation, depicting values as segments carved from a circular shape. As pie charts usually don't include explicit value labels around their circumference, it can be challenging to precisely determine the size of each slice. Nevertheless, both the pie chart and its variation, the donut plot, are particularly effective at emphasizing that the primary focus of the visualization should be the comparison of parts to the whole.
- **Map Plot:** There are various categories of specialized plots organized by their intended applications, and in concluding this article, we'll briefly explore one of them: map-based or geospatial plots. When data points within a dataset are associated with real geographic locations, it can be quite beneficial to visually represent them using a map. A prevalent example of this category is the choropleth map, similar to the one depicted above. In this approach, value is represented through colour, adopting a heatmap style, but instead of arranging values in a grid, they are assigned to specific regions on the map.
