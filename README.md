# Mobile_data_analysis


### Dashboard Link : https://app.powerbi.com/groups/me/reports/d8db7dea-fc5b-4685-8a0d-ac9b1fb62727/57081d8db673c755100e?experience=power-bi

## Problem Statement

With the rapid advancement in technology and frequent launches of new laptop models, it becomes difficult for consumers to make informed decisions based on specifications, price, and brand. Often, data related to laptops is scattered across platforms and lacks a centralized, interactive source for comparative analysis. This project aims to address this issue by building a comprehensive Power BI dashboard that helps users analyze and compare laptop models based on price, RAM, processor types, and other key specifications.

The project involves collecting data from SharePoint, cleaning and transforming it using Power BI and ChatGPT, and creating interactive visuals such as bar charts, slicers, and drill-through filters. Advanced DAX functions like CONCATENATE, IF, LEN, LEFT, SUMMARIZE, and AVERAGE were used for data modeling. Bookmarking techniques enhance navigation across multiple analysis pages like Overview, Price Analysis, and Feature vs Price comparison. Additionally, currency conversion and region-specific bookmarks (India and Dubai) are included to support cross-regional pricing insights.

This dashboard not only aids buyers but also assists retailers and analysts in identifying market trends, popular configurations, and price distribution effectively.

### Steps followed 

Project Setup & Account Creation

1. Created a Microsoft 365 trial account.

Signed in and placed an order for the trial.

Assigned licenses and set up SharePoint.

2. Data Loading & Integration

Created a SharePoint site and uploaded the dataset.

Connected SharePoint data to Power BI Desktop.

3. Data Cleaning & Preparation

Removed duplicate rows and unnecessary columns.

Used ChatGPT to clean the PKR Price column.

Cleaned and converted data types in the RAM column.

Trimmed extra characters in RAM values.

4. Report Page Design

Designed the Overview page layout.

Added and formatted slicers for filtering by brand and specs.

Inserted shapes and visual elements for better UX.

5. Data Visualization

Created bar charts for model count by company and processor types.

Added a table visual and drill-through filter.

Built a Price Analysis page with slicers and bookmarks.

6. Advanced Data Modeling

Cleaned the Launch Price column.

Used ChatGPT to generate a currency conversion factor table.

Added columns for price in INR and AED.

7. Bookmarking & Navigation

Created bookmarks for India and Dubai views.

Designed a Feature vs Price Comparison page.

Added navigation buttons using bookmarks.

8. DAX Implementation

Used CONCATENATE, LEN, IF, and LEFT for custom columns.

Applied SUMMARIZE and AVERAGE for aggregations.

9. Publishing

Published the final report to Power BI Service for sharing and collaboration.


Snapshot of Dashboaboard:

Overview:

![Image](https://github.com/user-attachments/assets/b80982d4-ce0e-40af-9622-d5f20d168c38)

Camera Resolution Details:

![Image](https://github.com/user-attachments/assets/4c252f14-d877-49dc-a0d2-72a65c879dab)

Price Analysis:

![Image](https://github.com/user-attachments/assets/d052a912-0232-4d76-a5df-386e63d72652)

Feature vs Price:

![Image](https://github.com/user-attachments/assets/07abe417-aa55-43ce-8a73-69b49180df80)

Matrix Visual:

![Image](https://github.com/user-attachments/assets/1b2e8575-f940-4330-8824-ed1058fec36a)




