# Jewelry ERP: A Data-Driven Approach to Luxury Manufacturing

This project is a practical exploration of how database architecture can drive business decisions in a niche industry. As a student of Economic Cybernetics, I wanted to move beyond simple data storage and build a system that actually answers critical business questions.

### The Problem
Managing a jewelry workshop involves more than just keeping track of inventory. It requires a precise understanding of the intersection between raw material costs (which fluctuate), specialized craftsmanship (man-hours), and the depreciation of expensive tech equipment like laser engravers.

### The Solution
I built this schema in Oracle SQL to simulate a real-world production environment. The architecture focuses on three main pillars:

1. Operational Integrity
The system uses strict constraints and relational logic to ensure that every gram of gold and every man-hour is accounted for. I implemented triggers to automate the boring parts, such as tracking price history, so that the data remains auditable without manual intervention.

2. Business Intelligence
Instead of just static tables, I wrote complex queries that act as internal tools:
- Price Advisor: A logic block that calculates the recommended luxury-tier price by factoring in production costs and a specific margin.
- Equipment ROI: A tracking system that measures how many services a specific machine has performed versus its initial investment cost.
- Supply Chain Alerts: A proactive check that compares current stock against the requirements of the entire product catalog.

3. Performance and Scalability
Because data is useless if it is slow, I included indexing on high-traffic columns like order dates and product names - building for performance from day one, not as an afterthought.


![Database Schema](db_diagram.png)


### Technical Implementation
The system is built on Oracle SQL and utilizes:
- Relational schema design with deep foreign key integrity.
- PL/SQL blocks for system resets and data management.
- Analytical views for real-time reporting.
- Triggers for automated data auditing.

I see this project as a bridge between economic theory and software engineering - a way to turn raw SQL into a strategic asset.

*Note: This project was developed to simulate a real-world tech-driven jewelry workshop workflow.*
