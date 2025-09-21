# Tailwind Traders Executive Dashboard

## Overview
The Tailwind Traders Executive Dashboard is a Power BI solution developed as part of the Coursera Microsoft PowerBI Data Analyst course. This dashboard provides actionable insights into the global performance of Tailwind Traders by curating sales and profit data, including visualizations for product quantities, median sales trends, net revenue, and yearly profit margins. It is optimized for both desktop and mobile access, ensuring executives can monitor performance on the go. The dashboard includes automated alerts and subscriptions to deliver timely updates.

- **Created On**: September 21, 2025
- **Author**: [Paridhi Singh]
- **Course**: Microsoft PowerBI Data Analyst (Coursera)
- **Tools**: Power BI Desktop, Power BI Service,Microsoft Excel
- **Data Source**: Tailwind Traders Report.pbix (derived from Excel data)

## Business Problem
Tailwind Traders faces challenges in maintaining visibility into its global sales and profit performance amidst fluctuating market conditions. Key issues include:
- Difficulty in identifying high-performing products and countries due to scattered data.
- Lack of real-time insights into profit margins, leading to delayed strategic decisions.
- Inconsistent monitoring of gross revenue trends, risking missed opportunities or financial downturns.
- Limited mobile accessibility for executives, hindering on-the-go decision-making.

This dashboard addresses these problems by consolidating data, providing automated alerts, and ensuring mobile compatibility.

## Insights
The dashboard delivers the following actionable insights:
- **Sales Performance**: Identifies the **UAE**  as country with the highest median sales  and **Floral Wallpaper** , **Procelian Dinner Set** and **ProCarpenter Toolkit** as top-selling products by quantity, enabling targeted marketing efforts.
- **Profit Trends**: Highlights **Modular Sofa Set** as the products with the highest net revenue and **October** has lowest Yearly profit margins , suggesting areas for cost optimization.
- **Revenue Monitoring**: Tracks YTD profit and gross revenue USD, with a daily alert for values below $400, allowing proactive financial management.
- **Global Comparison**: Shows yearly profit margin variations by country, aiding in resource allocation to high-margin regions.


## Installation and Setup

### Prerequisites
- **Power BI Desktop**: Install the latest version from [powerbi.microsoft.com](https://powerbi.microsoft.com/desktop/).
- **Power BI Service Account**: A Pro or Premium license is required for sharing and subscriptions.
- **Data File**: The "Tailwind Traders Report.pbix" file, created during the exercise.

### Steps to Set Up
1. **Download the PBIX File**:
   - Obtain the "Tailwind Traders Report.pbix" file from the project source or recreate it following the exercise steps from the Coursera course.

2. **Open in Power BI Desktop**:
   - Launch Power BI Desktop and open the "Tailwind Traders Report.pbix" file via **File** > **Open**.

3. **Publish to Power BI Service**:
   - In Power BI Desktop, go to **Home** > **Publish**.
   - Select your workspace (e.g., "My Workspace") and click **Select**.
   - Sign in to Power BI Service and verify the report upload.

4. **Configure Dashboard**:
   - In Power BI Service, create a new dashboard named "Tailwind Traders Executive Dashboard".
   - Pin visuals from the "Sales Overview" and "Profit Overview" tabs as outlined in the course exercise.

5. **Set Up Alerts and Subscriptions**:
   - For the "Sum of Gross Revenue USD" KPI, create a daily alert for values below $400 (frequency: every 24 hours).
   - Set up subscriptions:
     - "Sales Weekly Summary": Weekly on Mondays at 5:00 AM, starting September 21, 2025, ending December 31, 2025.
     - "Profit Weekly Summary": Weekly on Mondays, Wednesdays, and Fridays at 6:00 AM, same date range.

## Usage
- **Accessing the Dashboard**:
  - Log in to Power BI Service and navigate to the "Tailwind Traders Executive Dashboard" under your workspace.
  - Switch to **Mobile view** (phone icon) to see the optimized layout.
- **Interacting with Visuals**:
  - Use slicers (e.g., date filters) to explore data dynamically.
  - Note the product with the highest net revenue and the country with the highest median sales for strategic insights.
- **Receiving Updates**:
  - Check emails for subscription updates and alert notifications based on the configured schedules.

## Visualizations
- **Sales Overview**:
  - Loyalty Points by Country (Bar Chart)
  - Quantity Sold by Product (Column Chart)
  - Median Sales Distribution by Country (Pie Chart)
  - Median Sales Over Time (Line Chart)
  - Cards: Sum of Stock, Sum of Quantity Purchased, Median Sales
- **Profit Overview**:
  - Net Revenue by Product (Bar Chart)
  - Yearly Profit Margin by Country (Donut Chart)
  - Yearly Profit Margin Over Time (Area Chart)
  - Cards: YTD Profit, Sum of Net Revenue USD
  - KPI: Sum of Gross Revenue USD


  - **Screenshots**:
    
    
  - ![Desktop Sales Overview](https://github.com/paridhisingh18/tailwind-traders-executive-dashboard-excel-powerbi/blob/main/Dashboard%20Snapshots/Sales%20Overview.png)

  - ![Desktop Profit Overview](https://github.com/paridhisingh18/tailwind-traders-executive-dashboard-excel-powerbi/blob/main/Dashboard%20Snapshots/Profit%20Overview.png)

## Mobile Layout
- **Cards and KPI**:
  - Left: Sum of Net Revenue USD, Median Sales
  - Right: Sum of Quantity Purchased, YTD Profit
  - Full Width: Sum of Gross Revenue USD KPI
- **Core Visuals**:
  - Sales: Loyalty Points, Quantity Sold, Median Sales Distribution, Median Sales Over Time
  - Profit: Net Revenue, Yearly Profit Margin by Country, Yearly Profit Margin Over Time


  - **Screenshot**:
  - ![Mobile View](https://github.com/paridhisingh18/tailwind-traders-executive-dashboard-excel-powerbi/blob/main/Dashboard%20Snapshots/Mobile%20Layout.png)

## Contributing
- **Suggestions**: Submit issues or feature requests via GitHub Issues.
- **Collaboration**: Fork the repository, make changes, and submit a pull request.

## Contact
- **Author**: [Paridhi Singh]
- **Support**: Reach out via Power BI Service support, Coursera course forums, or your organization’s IT team.

## Acknowledgments
- Thanks to the Coursera Microsoft Power BI Analyst course team for the structured exercises and guidance.
- Gratitude to Tailwind Traders for the dataset and scenario.
- Built with assistance from Power BI community resources and documentation.
