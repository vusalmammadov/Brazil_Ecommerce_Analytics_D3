# Brazil E-Commerce Analytics (D3)

An interactive e-commerce analytics project built with **Microsoft Power
BI**, featuring a **D3.js Sankey diagram** to explore order and payment
flow.

## Project Overview

This project analyzes Brazilian e-commerce performance through an
executive-style dashboard. It brings key business indicators and visual
analysis together to help users explore sales performance, customer
activity, product categories, and delivery delays.

## Dashboard

The **Executive Overview** page presents the main performance indicators
and supporting visualizations in one view.

### Key Performance Indicators

-   **Total Sales** -- overall sales value
-   **Total Orders** -- number of orders
-   **Total Customers** -- number of customers
-   **Total Products** -- number of products
-   **Average Review Score** -- average customer review score

### Visualizations

  -----------------------------------------------------------------------
  Visualization           Purpose                 Technology
  ----------------------- ----------------------- -----------------------
  Monthly Sales Trend     Tracks sales            Power BI
                          performance over time   

  Sales by Product        Compares sales across   Power BI Treemap
  Category                product categories      

  Late Orders by Year and Shows how late orders   Power BI
  Month                   change over time        

  Payment / Order Flow    Illustrates the flow    D3.js Sankey
                          between payment-related 
                          stages and order flow   
  -----------------------------------------------------------------------

> The Sankey diagram is the D3.js-based visualization in this project.
> The other visuals listed above are standard Power BI visuals.

## Tools & Technologies

-   Microsoft Power BI
-   D3.js (Sankey diagram)
-   Data visualization and dashboard design

## Repository Contents

The repository is intended to contain:

``` text
Brazil_Ecommerce_Analytics_D3/
├── Brazil_Ecommerce_Analytics_D3.pbix
├── README.md
└── images/
    └── dashboard.png
```

*The file and folder names above describe the recommended repository
structure. Add the PBIX file and dashboard screenshot to the repository
when ready.*

## How to View the Project

1.  Download or clone this repository.
2.  Open `Brazil_Ecommerce_Analytics_D3.pbix` using Microsoft Power BI
    Desktop.
3.  Review the **Executive Overview** dashboard.
4.  Explore the D3.js Sankey visualization to inspect the payment/order
    flow.

## Project Goals

-   Present e-commerce performance through clear, business-focused KPIs.
-   Identify sales trends and category-level performance.
-   Monitor late-order patterns over time.
-   Use a D3.js Sankey diagram to make flow relationships easier to
    understand.

## Notes

-   The Power BI report (`.pbix`) is required to interact with the
    dashboard.
-   The dashboard screenshot is provided as a quick preview when the
    `images/dashboard.png` file is added.
-   This repository documents the current project scope; additional
    analyses or visuals can be added in future updates.

------------------------------------------------------------------------

**Project:** Brazil E-Commerce Analytics (D3)\
**Primary platform:** Microsoft Power BI\
**D3.js component:** Sankey diagram
