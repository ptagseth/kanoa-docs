---
id: kpim-view
title: View Matrix
sidebar_position: 4
hide_table_of_contents: true
---


In the KPI Matrix view - you will be able to see the matrix as configured with the data from the selected Tags.  There are options for data intervals, how to group the data, and for how the data will be presented.


![kpi-matrix](/img/kpi-matrix/ViewMatrix.png)

#### Sample Use Case:
1. Select a Matrix
2. Set the time period for data
3. Set data aggregation interval (default 1 hr)
4. Check choices for Ignore Zeros and Show Summary
5. Set Row vs Column view
 6. Click Get Data - bring in data
7. Select Data tag(s) to inspect further
8. Click Trend Views


![kpi-matrix](/img/kpi-matrix/MatrixButtons.png)


### Filters and Data View Parameters
- Matrix Selector - select the Matrix to be presented.  Use the search function to search in folders.
- Data period - select the time period for the data to be presented - choices are today, yesterday, this week, last week, this month, etc.  Or set a custom time period.  Set the start date and time and end date and time.
- Data Aggregation Interval - select the data interval for the aggregated data.  The data is aggregated in intervals of 1 hr, 30 mins, 15 mins. 1 hour is the default.
- Group by Shift, Run or Crew - this to sort by a specific Shift, Run or Crew.
- Group by Matrix Group. This can be utilized to organize the display of Matrix data in groups.
- Ignore Zeros - when this is checked, zero values will be ignored.  If all values for a tag are zero, the tag will not be displayed.
- Refresh Options / Auto Update - automatically update the table data whenever a filter parameter changes.
- Full Item Path - this will show the full data path when checked
- Item Info - this will show the data source (tag, calculation), unit type and default aggregation mode when enabled.
- Statistics - this will show the min, max, average, standard deviation, the calculated LCL and UCLs and the sum of the data in range.
- Item Spec - when enabled this will show the data item specifications set for control limits; LSL, LCL, target, and UCL and USL. 

### Alerts
- KPI Matrix data alerts - alerts are set when data are outside calculated or spec control limits.  Data values outside limits are color coded in the table.


### Left Menu icons
- Get Data - initiate a new data refresh.
- Clear table - Click this icon to clear the displayed data.
- Export data - Click the export button to export the data displayed in Excel format.
- Trend View - Select a single data tag and plot the trend over a time period.
- Production View - Select multiple data tags to plot the views over a time period.

## SPC charts
SPC (Statistical Process Control) is method of measuring and controlling quality by monitoring the manufacturing process. Quality data is collected in the form of product or process measurements or readings from various machines or instrumentation. The data is collected and used to evaluate, monitor and control a process. SPC is an effective method to drive continuous improvement.
We provide two different charts with an insight to the data, with analysis rules included to point out data abnormalities, inconsistencies and other non-random conditions:

### Trend View
Trend Views displays a single tag over a chosen time period.
- Time Series - Select the Time Series format to plot the data in a time series.  Nelson and WECO rules applies to determine data abnormalities.
  - Nelson Rules are a method to determine if some measured variable is out of control (unpredictable vs consistent).
        Read more about the Nelson Rules here:  https://en.wikipedia.org/wiki/Nelson_rules
  - WECO Rules are used to detect out of control, non-random conditions in your control charts.
    Read more about the WECO (Western Electric) Rules here:  https://en.wikipedia.org/wiki/Western_Electric_rules
- Bar Chart - Select the Bar format for the data to be displayed in bar chart.
- Histogram - select a data tag to show the distribution of the data.  Select Min and Max values to limit outliers.
- Table - Select the Table format for data in raw table format
- Export data - click the export button to export the data in Excel format.

![kpi-matrix](/img/kpi-matrix/TrendView.png)

### Production View
This to view multiple plots of aggregated data over a chosen time period.  Select multiple data sets (use CTRL button to select multiple sets) to compare and click the Production View icon.  Select the desired view. Or use the selection tree to pick the data sets to plot.
- Time Series - select the Time Series format to plot the data in a time series.  Select the Separate plot box to separate the data series.
- Bar Chart - Select the Bar format for the data to be displayed in bar chart for comparison.  Click the Separate Plot to separate the data series.
- Table - Select the Table format for data in raw table format
- Export data - click the export button to export the data in Excel format.

![kpi-matrix](/img/kpi-matrix/ProductView2Plots.png)

