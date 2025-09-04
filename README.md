# Expense-report
1. *Project Title*: Personal Expense Tracking Dashboard

2. *Purpose*
To provide a comprehensive view of monthly and category-wise expenses, enabling users or businesses to track spending patterns, monitor balances, and analyze financial behavior effectively.

3. *Tech Stack* :

   i. Power BI Desktop – Used to design and build the interactive dashboard with visuals and KPIs.

   ii. Power Query (M Language) – Performed data cleaning, transformation, and shaping before loading into the model.

   iii. DAX (Data Analysis Expressions) – Created calculated columns, measures, and KPIs for revenue, profit, and margin analysis.

   iv. Data Modeling – Built relationships between tables and applied star schema for efficient performance.

   v. Power BI Visuals – Designed charts, maps, and KPIs for trend analysis and regional insights.

4. *Business Problem*
   
   i. Many individuals and organizations struggle with:

   ii. Lack of visibility into where money is being spent.

   iii. Difficulty in identifying overspending categories.

   iv. Inability to track expenses vs. available balance over time.

   v. Challenges in planning future budgets due to unstructured data.

This leads to poor financial planning, missed savings opportunities, and inefficiency in managing resources.

   *Goal of the dashboard*
   
   i. Consolidate all expense data into a single interactive dashboard.
      
   ii. Track total spends, average monthly spends, and balances over time.
     
   iii. Categorize expenses (Bills, Credit Card, EMI, Investments, etc.) to identify spending patterns.
      
   iv. Provide actionable insights to optimize financial decisions and budgeting.

5. Walkthrough of Dashboard Visuals

   5a. KPI Cards (Top Row)
  
      i. Total Spends (842K) → Shows the cumulative money spent across all categories in the selected period.
   
      ii. Total Credit Amount (810K) → Displays cumulative amount credited to the account.
   
      iii. Average Monthly Spend (210K) → Provides a quick benchmark of monthly financial outflow.
   
   Purpose: These KPIs give an at-a-glance snapshot of financial health.

  5b. Walkthrough of Slicer & Buttons
    
   i. Month Slicer (January, February, March, April)
    What it does:
    This slicer allows users to filter all visuals in the dashboard by a specific month.
    -For example, selecting February will update:
    
   Purpose:
       
   a.Gives flexibility to analyze expenses month by month instead of looking at the entire period.
      
   b.Helps identify seasonal spikes or monthly patterns.

   ii. Balance Button:
     
   a. Displays the Balance by Date (Line Chart) visual.
   
   b. This chart highlights how much money remained on different dates after spending.
   
   c. Useful for monitoring liquidity and seeing if balances stayed stable or dropped drastically.

   iii. Spend Button:
     
   a. Replaces the chart with a Spend by Date (Line Chart) visual.
   
   b. Instead of balance, this shows how much was spent daily over the months.
   
   c. Useful for identifying spending peaks (e.g., large bills, EMI deductions, or shopping spikes).

   Purpose of Buttons:
   These toggle views allow users to switch between two perspectives:
    
   a. Balance View → How much is left.
    
   b. Spend View → How much was spent.
   Instead of crowding the dashboard with multiple charts, bookmarks provide a clean, interactive experience.

 5c. Monthly Spend by Category (Bar Chart, Bottom Left)
  
   i. Groups expenses by Bills, Credit Card, EMI, Investment, and Others.
  
  ii. Compares month-on-month category trends (Jan–Apr).
  Example: February has a huge spike in Bills, while March has higher EMI.
  Purpose: Identifies categories driving expenses and their seasonality.

5d. Monthly Spend by Category (Donut Chart, Top Right)
Breaks down the percentage contribution of each category to total spend.
Example: Bills (28.7%) and Others (24.15%) are the largest spend buckets.
Minor categories like Movies (0.25%) show discretionary spending.
 Purpose: Gives a proportional view of spending habits, highlighting where most money goes.

5e. Monthly Spend by Category & Month (Matrix Table, Bottom Right)
Shows a detailed breakdown by category across each month.
Example:
  
  i. February → unusually high Bills (130K).
  
  ii. March → peak Credit Card Bill (71K).
  
  iii. April → surge in Others (71K).
 Color formatting highlights high vs. low spends for quick spotting.
 Purpose: Allows deep-dive into specific categories and months to pinpoint unusual spikes.

Business Impact of Expense Dashboard
1. Improved Financial Visibility
Consolidates all expenses into one dashboard, eliminating the need to check multiple statements or reports.
Provides a real-time, holistic view of spends, balances, and credit usage.

3. Better Cost Control
   By analyzing monthly and category-wise spending, businesses/individuals can identify overspending areas (e.g., Bills, Credit Card, Others).
   Enables proactive action like renegotiating vendor bills, cutting unnecessary costs, or adjusting budgets.

3.Enhanced Budget Planning
With KPIs like Average Monthly Spend, financial planners can forecast future budgets more accurately.
Helps align actual expenses with budgeted targets.

4. Cash Flow Management
Balance by Date trend ensures businesses/individuals don’t run into liquidity issues.
Provides early warning signs of cash shortages when expenses rise faster than income.

5. Decision-Making Efficiency
Interactive slicers and bookmark buttons (Balance/Spend toggle) let decision-makers quickly shift perspectives without going through lengthy reports.
Saves time and makes insights more accessible to non-technical stakeholders.

6. Supports Strategic Growth
Identifying investment vs. expense ratio helps evaluate whether funds are being allocated towards growth (Investments) or liabilities (Bills/EMIs).
Encourages smarter long-term financial planning.

Screenshot/Demo: ![Dashboard Preview](https://github.com/anushagc04-pbi/Expense-report/blob/main/Snapshot%20of%20the%20expense%20report.png)
