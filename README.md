# Operation Theater Insights

![Operation Theater Insights Dashboard](https://github.com/user-attachments/assets/7e73be87-3a6e-4756-a666-a265b63c8a5c)

## Overview

Operation Theater Insights is a comprehensive data visualization project aimed at helping healthcare professionals analyze and optimize the utilization of operating rooms. This project provides detailed metrics and visualizations related to surgical operations, enabling better decision-making and operational efficiency.


## Features

- **Total Surgeries and Average Timing Differences**
  - Displays the total number of surgeries and the average difference in surgical timing.

- **Comparison of Average Delay, Waiting, and Surgical Timing by Operating Room**
  - Visualizes the average delay time, waiting time, and surgical timing differences across different operating rooms.

- **Total Delay Time by Day of the Week**
  - Shows the sum of delay times for each day of the week, helping to identify patterns.

- **Top Procedures by Department**
  - Highlights the most common procedures performed by each department.

- **Average Waiting Time by Medical Service**
  - Displays the average waiting time for each medical service.

- **Percentage of Total Delay Time by Medical Service**
  - Breaks down the total delay time percentage for each medical service.

## Technologies Used

- **Data Visualization**: Power BI
- **Data Source**: CSV files, databases, and other data formats
- **Metrics Calculation**: DAX (Data Analysis Expressions)

## Dataset and Power BI File

You can find the dataset and the Power BI file on GitHub:
- [GitHub Repository](https://github.com/saikrupa82/Operation-Theater-Insights)
### Additional Resources

You can read more about this project and its analysis on Medium: [Link to Medium Post](https://medium.com/@saikrupar82/analyzing-operation-theater-insights-with-data-visualization-1ee68f56627d)

## Installation

To get started with the project, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/saikrupa82/Operation-Theater-Insights.git
   cd Operation-Theater-Insights```


2. **Open the Power BI file**

Open the provided Power BI file (`Operation_Theater_Insights.pbix`) using Power BI Desktop.

3. **Load the dataset**

Ensure the dataset (`2022_q1.csv`) is placed in the appropriate directory and linked correctly in Power BI.

### How to Use the Dashboard

1. **Filter Data**

Use the interactive filters at the top of the dashboard to slice data by different dimensions such as year, month, quarter, day of the week, operating room, and medical service.

2. **Analyze Metrics**

Review the various visualizations to understand the distribution of delay times, waiting times, and surgical timings across different parameters.

3. **Identify Patterns**

Look for patterns in the data to identify areas for improvement in scheduling and operations.

### Analysis from CSV Data

In addition to the Power BI dashboard, a CSV file containing detailed operational data was analyzed. Key findings include:

- **Total Surgeries**: 2172 surgeries performed over the analyzed period.
- **Average Surgical Timing Difference**: 32 minutes.
- **Medical Service Delay Analysis**: 
  - ENT: 9%
  - General: 6%
  - OBGYN: 8%
  - Orthopedics: 17%
- **Procedure-Specific Insights**: Top procedures contributing to delay times included Tonsillectomy, Tympanostomy, Myringotomy, and Sleeve Gastrectomy.

### Performance Analysis

Using Power BI's Performance Analyzer, the refresh times of various visual elements were assessed:

- **Slicer Interactions**: Updates took approximately 213-216 milliseconds each.
- **Comparison of Average Delay, Waiting, and Surgical Timing by Operating Room**: This visual took the longest to refresh at 485 milliseconds.
- **Overall Performance**: The dashboard maintains a good balance of performance and interactivity.

### Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. **Fork the repository**
2. **Create your feature branch**: `git checkout -b feature/AmazingFeature`
3. **Commit your changes**: `git commit -m 'Add some AmazingFeature'`
4. **Push to the branch**: `git push origin feature/AmazingFeature`
5. **Open a Pull Request**
