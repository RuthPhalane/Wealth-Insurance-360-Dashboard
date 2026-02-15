# CityLife 360: Executive Wealth & Insurance Dashboard

## The Business Challenge
As a **Senior Business Intelligence Developer** at **CityLife Insurance**, I was tasked with translating a high-level executive request into a comprehensive, 360-degree analytical tool. 

The goal was to integrate fragmented data from both the Wealth and Insurance departments into a unified "command center." This supports the strategic priority of enhancing advisor performance and optimizing the product portfolio based on risk and profitability.

---

## Project Showcase

### 1. Executive Summary (The 360° View)
<img width="1408" height="799" alt="image" src="https://github.com/user-attachments/assets/28ae8255-91bd-4d95-9e70-6e685ef3319a" />


* **High-Level KPIs:** Real-time tracking of Current Year (CY) Sales, Withdrawals, and Net Sales with YoY comparisons.
* **Integrated Breakdowns:** Dynamic visuals showing Sales by Business Line (Life, House, Car Insurance) and Product Risk Level.

### 2. Wealth & Advisor Deep Dive
<img width="1435" height="804" alt="image" src="https://github.com/user-attachments/assets/567053b1-af72-4be1-b445-41dc7c9b8dc9" />

* **Advisor Performance:** Individual performance metrics (CY vs. PY) and regional benchmarking (Treemap) to identify top performers.
* **Contract Analysis:** Waterfall charts depicting sales contributions by contract type (Full-time, Part-time, Contract).

---

## Technical Workflow

### 1. Advanced Data Modeling (Star Schema)
To handle the complexity of multi-departmental data, I designed a high-performance **Star Schema**.
* **Fact Tables:** Sales, Withdrawals, and Net Sales ledger.
* **Dimension Tables:** Advisor Details, Geography (Regions), Product Catalog, and a custom Calendar table for time-intelligence.

### 2. Analytical Intelligence (DAX)
I developed a library of complex DAX measures to drive the dashboard's interactivity:
* **Dynamic Measure Selection:** Implemented a "Measure Selector" using field parameters, allowing users to switch the entire report context between Sales, Withdrawals, and Net Sales.
