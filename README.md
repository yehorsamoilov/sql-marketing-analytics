# E-commerce Conversion Analysis

## Project Overview
This SQL script consolidates data from 7 different tables in BigQuery to build a robust session-level data mart. It tracks user interactions from landing to final purchase.

## Key Technical Features
- **Multi-table Joins:** Integrated sessions, account details, product info, and event logs.
- **Custom Segmentation:** Categorized traffic sources and user types using `CASE` and `IF` logic.
- **Funnel Visualization Ready:** Aggregated event data into binary flags to calculate Conversion Rates (CR) for each stage.

## Usage
The output table is designed for BI tools (like Looker or Tableau) to analyze drop-off rates across different devices and marketing channels.
