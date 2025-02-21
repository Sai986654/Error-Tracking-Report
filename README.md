# Integration Error Tracking Report

This repository contains a Power BI report that tracks integration errors between two systems. The report helps in monitoring and analyzing the errors to ensure smooth data transfer.

## Overview

- **Project**: Data transfer between two systems
- **Purpose**: Track and analyze integration errors
- **Tools Used**: Power BI

## Visualizations Used

- Bookmarks
- Slicers
- Donut Charts
- Bar Graph
- Heat Map (DENEB)
- Page Navigator
- Navigator Buttons
- Other visualizations

## First Page

The first page provides a high-level summary of integration errors, including:

- **Total Errors**: Displays the total number of integration errors recorded.
- **Error Trends**: A line chart showing the trend of errors over time.
- **Top Error Types**: A bar chart highlighting the most common types of errors.
- **Error Details Table**: A detailed table listing individual errors with columns for:
  - **Timestamp**: The date and time when the error occurred.
  - **Error Message**: A brief description of the error.
  - **Affected System**: The system that was affected by the error.
  - **Status**: The current status of the error (e.g., resolved, pending).
- **Filters**: Interactive filters to allow users to drill down into specific time periods, error types, or affected systems.

**Views Used**: IntegrationErrorsView, SystemStatusView, ErrorFrequencyView
![image](https://github.com/user-attachments/assets/f3c0723d-a54e-4cb9-a373-60232feabbf9)

## Second Page

The second page offers a detailed analysis of integration errors, featuring:

- **Error Categorization**: 
  - **Pie Chart**: Displays the distribution of errors by category.
  - **Bar Chart**: Shows the number of errors by type.
- **Error Details Table**: A detailed table listing individual errors with columns for:
  - **Error ID**: A unique identifier for each error.
  - **Error Message**: A brief description of the error.
  - **Timestamp**: The date and time when the error occurred.
  - **Affected System**: The system that was affected by the error.
  - **Resolution Status**: The current status of the error (e.g., resolved, pending).
- **Interactive Filters**: 
  - **Date Range Selector**: Allows users to filter errors by a specific date range.
  - **Error Type Filter**: Enables users to filter errors by type.
  - **System Filter**: Allows users to filter errors by the affected system.

**Views Used**: ErrorDetailsView, ErrorCategoryView, ErrorTrendView

*An external link was removed to protect your privacy.* 
## Third Page

The third page focuses on trend analysis with:

- **Trend Analysis Graph**: Displays the event count on the y-axis and the date on the x-axis, showing data points over time with significant spikes and patterns.
- **Interactive Filters**: 
  - **Select Relative Date**: A dropdown menu for selecting different time ranges.
  - **Search Failure Reason**: A search bar for searching specific failure reasons.
- **Detailed View Button**: Provides a more in-depth analysis or additional details when clicked.

*An external link was removed to protect your privacy.* 
## Fourth Page

The fourth page includes various analyses and details, such as:

- **Total CustomerUpdated Issues**: Displays the total number of customer-updated issues in the current year.
- **Error Analysis by Categorization**: Provides analysis of errors by categorization.
- **POC Details**: Details of the point of contact for specific errors.

**Tabs**: Integration Overview, Error Details, Q&A, Rate SNOW

*An external link was removed to protect your privacy.* 
## How to Use

1. Download the report file from this repository.
2. Open the report in Power BI Desktop.

## Note

All sensitive information has been removed from the report.
