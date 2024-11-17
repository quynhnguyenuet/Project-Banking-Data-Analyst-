# DASHBOARD LIMIT MANAGEMENT
## by Nguyen Quynh

This project uses SQL to analyze data and then transfers the data to Excel for visualization, providing deeper insights into bank limit information.

## Content Summary
1. **REVOLVING LIMIT OVERVIEW**:
   - Provides an overall view of different types of limits, including new limits, renewals, and utilization limits.
   - The change in limit from the beginning of the period to the end of the period will give viewers the most comprehensive overview of the current limit situation.
   <div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/quynhnguyenuet/Project-Banking-Data-Analyst-/blob/main/LIMIT%20DASHBOARD/image/Overview.png" style="width: 150%;"/>
   </div>

2. **NEW LIMIT**:
   - The new limit is understood as the limit of non-credit customers for the last 12 months.
   - The new limit is tracked from the document circulation system until the limit is successfully accounted for and activated.
   - The DB also provides information about the status of new pending applications at any stage so that reasonable actions can be taken for these applications.
   <div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/quynhnguyenuet/Project-Banking-Data-Analyst-/blob/main/LIMIT%20DASHBOARD/image/New%20limit.png"/>
   </div>

   - In addition, viewers can monitor the new issuance situation, including the value and number of new customers granted monthly, by region, the number of records on the document circulation system, as well as detailed data.
   <div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/quynhnguyenuet/Project-Banking-Data-Analyst-/blob/main/LIMIT%20DASHBOARD/image/Chi%20tiet%20new%20limit.png"/>
   </div>

3. **RENEWAL LIMIT**:
   - Provides the status of customers due for re-issue in the month compared to the current status of documents on the document circulation system, as well as the status of re-issue, limit accounting, and limit activation.
   <div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/quynhnguyenuet/Project-Banking-Data-Analyst-/blob/main/LIMIT%20DASHBOARD/image/renewals%20limit.png"/>
   </div>
   - Details of reissue status for each month in each region and cases due for reissue in the following months.
   <div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/quynhnguyenuet/Project-Banking-Data-Analyst-/blob/main/LIMIT%20DASHBOARD/image/chi%20tiet%20renewals%20limit.png"/>
   </div>

4. **UTILIZATION LIMIT**:
   - Provides an overview of limit usage, total limit, loan limit by each customer segment, comparison of increase or decrease between the beginning and end of the period, and credit matrix.
   <div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/quynhnguyenuet/Project-Banking-Data-Analyst-/blob/main/LIMIT%20DASHBOARD/image/utilization%20limit.png"/>
   </div>
   - Detailed utilization limit each month, each region of total limit, loan limit, guarantee limit, LC limit, and detailed data per customer.
   <div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/quynhnguyenuet/Project-Banking-Data-Analyst-/blob/main/LIMIT%20DASHBOARD/image/Chi%20tiet%20utilization%20limit.png"/>
   </div>

5. **NON-REVOLVING LIMIT**:
   - Provides the shape of non-revolving limits compared to revolving limits each month, with detailed data per customer.
   <div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/quynhnguyenuet/Project-Banking-Data-Analyst-/blob/main/LIMIT%20DASHBOARD/image/HM%20mon.png"/>
   </div>
   - Details of non-revolving limits, including LC loan guarantees.
   <div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/quynhnguyenuet/Project-Banking-Data-Analyst-/blob/main/LIMIT%20DASHBOARD/image/Chi%20tiet%20hm%20mon.png"/>
   </div>
