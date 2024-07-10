# Control charts

Control charts are a fundamental tool in statistical process control (SPC). They're used to monitor the stability and consistency of a process over time by plotting data points and determining if they fall within statistical control limits. Typically, control charts involve plotting sample statistics such as means, ranges, or proportions against predefined control limits. They help distinguish between common cause variation (inherent to the process) and special cause variation (due to external factors or anomalies), allowing organizations to maintain process stability and identify when intervention is needed.

## Variations:
- variables charts: **$\bar{X}$ and R** chart (also called averages and range chart), **$\bar{X}$ and s** chart, **chart of individuals** (also called X chart, X-R chart, IX-MR chart, XmR chart, moving range chart), **moving average–moving range** chart (also called MA–MR chart), **target charts** (also called difference charts, deviation charts, and nominal charts), **CUSUM** (also called cumulative sum chart), **EWMA** (also called exponentially weighted moving average chart), **multivariate chart** (also called Hotelling T$^2$)
- attributes charts: **p chart** (also called proportion chart), **np chart**, **c chart** (also called count chart), **u chart**.

## Description:
The control chart (also called: statistical process control) is a graph used to study how a process changes over time. Data are plotted in time order. A control chart always has a central line for the average, an upper line for the upper control limit, and a lower line for the lower control limit. These lines are determined from historical data. By comparing current data to these lines, one can make conclusions about whether the process variation is consistent (in control) or is unpredictable (out of control, affected by special causes of variation).

## Control Chart Decision Tree:
- Variable data are measured on a continuous scale. For example, time, weight, distance, or temperature can be measured in fractions or decimals. The only limit to the precision of the measurement is the measuring device.
- Attribute data are counted and cannot have fractions or decimals. Attribute data arise when you are determining only the presence or absence of something: success or failure, accept or reject, correct or not correct.

## Basic Procedure:
1. Choose the appropriate control chart for your data.
2. Determine the appropriate time period for collecting and plotting data.
3. Follow the procedure for that control chart on the following pages to collect data, construct your chart, and analyze the data.
4. Look for out-of-control signals on the control chart. When one is identified, mark it on the chart and investigate the cause. Document how you investigated, what you learned, the cause, and how it was corrected.
    - A *single point* outside the control limits.
    - *Two out of three* successive points are on the same side of the centerline and farther than 2$\sigma$ from it.
    - *Four out of five* successive points are on the same side of the centerline and farther than 1$\sigma$ from it.
    - A run of *eight in a row* are on the same side of the centerline. Or *ten out of eleven*, *twelve out of fourteen*, or *sixteen out of twenty*.
    - Obvious consistent or persistent patterns that suggest something unusual about your data and your process.
5. Continue to plot data as they are generated. As each new data point is plotted, check for new out-of-control signals.
6. When you start a new control chart, the process may be out of control. If so, the control limits calculated from the first 20 points are conditional limits. When you have at least 20 sequential points from a period when the process is operating in control, recalculate control limits.

## Bibliography
- Tague, N., 2005. Quality Toolbox. 2nd ed. ASQ Quality Press, pp.155-196.