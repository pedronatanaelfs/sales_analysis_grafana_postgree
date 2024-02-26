# Sales Analysis in Grafana with Postgree

## Overview

This project is based on the [Sample Sales Data Dashboard](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data) available on Kaggle. The goal of this project is to connect the data from Kaggle to a PostgreSQL database and visualize it using Grafana. The resulting dashboard includes various visualizations providing insights into sales data.

## Project Details

1. **Data Source:**
   - The project utilizes the sample sales data available on Kaggle. You can find the original dataset [here](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data).

2. **Data Integration:**
   - The data from Kaggle is connected to a PostgreSQL database, facilitating efficient data storage and retrieval.

3. **Visualization with Grafana:**
   - The primary tool used for visualization is Grafana, a powerful open-source analytics and monitoring platform.
   - The dashboard exhibits the following characteristics:

### Dashboard Features:

![image](https://github.com/pedronatanaelfs/sales_analysis_grafana_postgree/assets/125995273/5c2f220f-9a1f-48ae-a300-39c16f58dddc)


- **Year Display:**
  - The dashboard prominently displays the year "2003" with user-friendly options to switch between different years.
  - Annotations and alerts enhance the dashboard's utility.

- **Total Orders & Revenue:**
  - Circular graphs showcase key metrics, with "Total Orders" presented as 1000 and "Total Revenue" as $3.52M.

- **Orders by Date & Status:**
  - A line graph illustrates order fluctuations across different months of the year.
  - A bar chart depicting "Order Status" reveals insights such as 979 orders shipped, none resolved, and 1 canceled.

- **Revenue by Product Line & Region:**
  - Horizontal bars represent "Revenue by Product Line" across various categories.
  - A world map visualization indicates "Revenue by Region" with green circles highlighting regions of sales; larger circles correspond to higher revenues.

## Tools Used

The project leverages the following tools and technologies:

- **PostgreSQL:**
  - Used for storing and managing the connected sales data.

- **Grafana:**
  - The primary platform for creating, exploring, and sharing interactive dashboards.

## Getting Started

To set up and explore the project locally:

1. **Clone the Repository:**
   - Clone this repository to your local machine.

2. **Database Setup:**
   - Ensure you have PostgreSQL installed.
   - Import the Kaggle sales data into your PostgreSQL database.

3. **Grafana Setup:**
   - Install Grafana and configure it to connect to your PostgreSQL database.
   - Import the Grafana dashboard provided in this repository.

4. **Explore the Dashboard:**
   - Open Grafana and navigate to the imported dashboard to explore the visualizations and gain insights from the sales data.

## Acknowledgements

Feel free to contribute, report issues, or provide feedback to enhance this project!
