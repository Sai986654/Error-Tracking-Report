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
![image](https://github.com/user-attachments/assets/f3c0723d-a54e-4cb9-a373-60232feabbf9)
The first page provides a high-level summary of integration errors, including:

- **Total Errors**: Displays the total number of integration errors recorded.
- **Error Trends**: A line chart showing the trend of errors over time.
- **Top Error Types**: A bar chart highlighting the most common types of errors.
- **Filters**: Interactive filters to allow users to drill down into specific time periods, country, or environment.

**Views Used**: CountryView(Donut chart), ErrorCountView

## Second Page
![image](https://github.com/user-attachments/assets/f9132086-c64b-448b-9065-745d47465e4b)

The second page offers a detailed analysis of integration errors, featuring:

- **Error Categorization**: 
  - **Pie Chart**: Displays the distribution of errors by category.
  - **Bar Chart**: Shows the number of errors by type.
- **Interactive Filters**: 
  - **Date Range Selector**: Allows users to filter errors by a specific date range.
  - **Error Type Filter**: Enables users to filter errors by type.
  - **System Filter**: Allows users to filter errors by the affected system.

**Views Used**: IntegrationErrorsView, HeatMapView(DENEB)

## Third Page
![image](https://github.com/user-attachments/assets/5dd5d92c-17ec-4416-88c8-64665599aa21)

The third page focuses on Error Details and trend analysis with:

- **Error Details Table**: A detailed table listing individual errors with columns for:
  - **Error ID**: A unique identifier for each error.
  - **Error Message**: A brief description of the error.
  - **Timestamp**: The date and time when the error occurred.
  - **Affected System**: The system that was affected by the error.
  - **Resolution Status**: The current status of the error (e.g., resolved, pending).
- **Trend Analysis Graph**: Displays the event count on the y-axis and the date on the x-axis, showing data points over time with significant spikes and patterns.
- **Interactive Filters**: 
  - **Select Relative Date**: A dropdown menu for selecting different time ranges.
  - **Search Failure Reason**: A search bar for searching specific failure reasons.
- **Detailed View Button**: Provides a more in-depth analysis or additional details when clicked.

**Views Used**: ErrorDetailsView, ErrorCategoryView, ErrorTrendView

## Fourth Page
![image](https://github.com/user-attachments/assets/05366a65-c650-46da-b8ef-44b13413c237)

The fourth page includes a Q&A visual, providing insights and answers related to the data:

- **Q&A Visual**: Allows users to ask questions and get answers based on the data.
- **Interactive Elements**: Includes various interactive elements to explore the data further.

## Fifth Page
![image](https://github.com/user-attachments/assets/d1993521-745a-4742-a1e2-09321fe29218)

The fifth page allows users to raise an incident to track any of the errors:

- **Incident Details**: A table listing details such as Integration ID, Failure Reason, Environment, Categorization, Latest Date, Owner, Assigned To, and Times Appeared last month.
- **Create Incident Button**: A button labeled "CREATE INCIDENT" to raise a new incident.

**Tabs**: Integration Overview, Error Details, Q&A, Rate SNOW

*An external link was removed to protect your privacy.* 
## How to Use

1. Download the report file from this repository.
2. Open the report in Power BI Desktop.

## Note

All sensitive information has been removed from the report.
