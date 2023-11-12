In this chapter, we're going to cover the following main topics:

What is a time series?
Data-generating process (DGP)
What can we forecast?
Forecasting terminology and notation


## What is a Time Series?

A time series is a sequence of data points gathered, recorded, or observed at regular intervals throughout a specific timeframe. In this context, each data point is linked to a specific timestamp or time period, enabling the organization of data chronologically.

Time series data finds applications in various domains, such as finance, economics, meteorology, sales, stock markets, healthcare, and more. Its primary purpose is to analyze historical patterns, identify trends, forecast future values, and comprehend the behavior of a phenomenon over time.

Time series data can be categorized as either continuous or discrete. Continuous time series data encompasses measurements with a range of possible values, like temperature readings or stock prices. Conversely, discrete time series data involves measurements limited to specific values or categories, such as daily sales counts or customer ratings.

Analyzing and visualizing time series data is vital for gaining insights, making predictions, and understanding the evolving dynamics of a system or process over time.

### Types of Time Series Data

Time series data can be classified into two main types based on its nature: continuous and discrete.

## A. Continuous Data

Continuous time series data involves measurements or observations that can take any value within a specified range. This type of data exhibits a continuous and uninterrupted flow of data points over time, prevalent in domains like temperature records, stock market values, sensor data, financial metrics, environmental monitoring, and physiological parameters. Visualization methods for continuous time series data include line plots, area charts, and smooth plots, enabling the observation of trends, fluctuations, and patterns.

## B. Discrete Data

Discrete time series data consists of measurements or observations limited to specific values or categories. This type of data does not have a continuous range but comprises distinct and separate data points. Examples of discrete time series data include counts of occurrences, categorical data, binary data, and rating scales. Bar charts, histograms, and stacked area charts are commonly employed visualization techniques for discrete time series data, facilitating an understanding of distribution, changes, and patterns over time.

### Ways for Time Series Data Visualization

To effectively visualize time series data, various techniques can be employed:

- Tabular Visualization: Presents time series data in a structured table format, providing a concise overview of the data.

- 1D Plot of Measurement Times: Represents measurement times along a one-dimensional axis, aiding in understanding temporal distribution and patterns.

- 1D Plot of Measurement Values: Displays variation in data values over time using line plots for continuous data and bar charts for discrete data.

- 1D Color Plot of Measurement Values: Represents variation in measurement values using colors on a one-dimensional axis for quick identification of high or low values.

<strong>Bubble Plot</strong>: Utilizes bubbles to represent data points, with size or color encoding specific measurement values, allowing the simultaneous representation of multiple variables.

<strong>Scatter Plot</strong>: Displays the relationship between two variables on a Cartesian plane.

<strong>Linear Line Plot, Linear Step Plot, and Linear Smooth Plot</strong>: Connect consecutive data points to emphasize trends, continuity, or reduce noise.

<strong>Area Chart</strong>: Fills the area between the line representing the data and the x-axis, useful for visualizing stacked time series data.

<strong>Horizon Chart</strong>: Condenses time series data into a horizontally layered representation, facilitating the comparison of multiple time series on a single chart.

<strong>Bar Chart</strong>: Represents discrete time series data using rectangular bars, effective for comparing values between different time periods or categories.

<strong>Histogram</strong>: Displays the distribution of continuous or discrete time series data by dividing the range into intervals (bins) and representing the frequency or count of data points within each bin.

## Best Platforms to Visualize Data

Several platforms support effective time series data visualization, including:

<strong>Microsoft Power BI</strong>: Offers a wide range of visualization capabilities specific to time series data, such as line charts, area charts, and scatter plots. Users can create interactive dashboards and reports.

<strong>Tableau</strong>: Widely used for exploring and presenting data, Tableau provides features like line charts, area charts, heatmaps, and maps for effective time series visualization. It supports interactive filtering, drill-down, and animation features.

<strong>R</strong>: An open-source programming language with packages like ggplot2, plotly, and graphs designed for time series analysis and visualization.

<strong>Excel</strong>: While not as advanced as dedicated platforms, Excel provides basic time series visualization capabilities through chart types like line charts, bar charts, and scatter plots.

## Time Series Data Visualization Examples

Some examples of time series data visualizations include:

<strong>Gantt Charts</strong>: Used to visualize project schedules or timelines, displaying tasks or events along a horizontal timeline.

</strong>Line Graphs: Effective for visualizing continuous time series data, connecting data points to observe trends, seasonality, or irregularities.

<strong>Heatmaps</strong>: Represent time series data using color intensity in a grid format, useful for visualizing patterns, correlations, or anomalies in multi-dimensional data.

<strong>Map</strong>: Plots data points on a map to visualize spatial patterns or changes in variables over time.

<strong>Stacked Area Charts</strong>: Display cumulative values or proportions of different variables over time, useful for visualizing composition or contribution.

In summary, understanding the nature of time series data and employing appropriate visualization techniques and platforms are essential for extracting meaningful insights and making informed decisions.





Resources:
- https://github.com/marcopeix/time-series-analysis
- 
