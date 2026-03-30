# Power BI Project – Retail Store Analysis

## Project Overview

This project analyzes customer purchase behavior across different store locations and settings in the United States. The dataset includes spending on categories such as Video Games, Indoor Sports, Outdoor Sports, Books, and Gadgets.

The objective is to build an interactive Power BI report and extract meaningful insights.


## Industry Type

Retail Store


## Dataset

Student Survey Dataset

Key fields:

* Age
* Store Location
* Store Setting
* InDoor SportKits
* OutDoor SportKits
* Gadgets
* Total Amount of Purchase

Additional Table:
User Mapping Table

* UserID
* Survey Location

This table is used to control data access for different users.


## Problem Statement

Create a Power BI report with the following visualizations and features:


## 1. Tabular Visualization

* Display total amount of purchase based on:

  * Store Location
  * Store Setting
* Apply conditional formatting:

  * TAP < 3000 → Red
  * 3000 ≤ TAP < 6000 → Yellow
  * TAP ≥ 6000 → Blue


## 2. Matrix Visualization

* Show amount spent on Outdoor Sports across:

  * Store Settings
  * Store Location
* Apply conditional formatting on Outdoor Sports values


## 3. Funnel Chart

* Display total purchase by Store Setting
* Show values as percentage of first


## 4. Pie Chart

* Show total purchase by Store Location
* Filter: Only Suburban Store Setting


## 5 a) Scatter Chart

* X-Axis: Video Games (Gadgets)
* Y-Axis: Outdoor Sports
* Legend/Details: Age Group

### b) Ribbon Chart

* Axis: Age Group
* Legend: Category (Indoor Sports and Video Games)
* Values: Spending


## 6. Row-Level Security (RLS)

* Implemented using User Mapping table
* Data access is restricted based on user roles

Example:

* Users assigned to Rural can only view Rural data
* Users assigned to Urban can only view Urban data
* Users assigned to Suburban can only view Suburban data


## 7. Q&A Feature

* Used Power BI Q&A to:

  * Analyze average age
  * Create a donut chart for total purchases by Store Location


## Data Model

* Student Survey table contains transactional data
* User Mapping table is used for security filtering
* Relationship established on location fields to enable row-level security


## Tools and Technologies

* Power BI
* DAX
* Power Query

## Key Insights

* Spending behavior varies across age groups
* Indoor and outdoor preferences change with age
* Store settings influence purchasing patterns

## Files Included

* project1.pbix


## Conclusion

This project demonstrates how Power BI can be used to analyze retail data, visualize trends, and derive insights using interactive dashboards.
