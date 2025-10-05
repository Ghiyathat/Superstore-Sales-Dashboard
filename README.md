## Superstore Sales Dashboard

### Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Tool](#tool)
4. [Dashboard Breakdown](#dashboard-breakdown)
5. [Dashboard](#dashboard)
6. [Key Skills](#key-skills)
7. [Conclusion](#conclusion)
8. [Reference](#reference)

### Project Overview
This Power BI dashboard is a 4-page interactive report designed to analyze sales performance across multiple years, regions, and catgories. Before creating the visuals, data transformation was performed on the data using Power Query, including:
- Standardizing date formats and extracting only date values from datetime fields
- Ensuring categorical fields were properly formatted for slicers and AI visuals
  
The result is an interactive , user friendly dashboard that allows users to explore sales data dynamically and gain actionabe insights

### Dataset
- [SuperStoreData-230102-093001.xlsx](https://github.com/user-attachments/files/22709408/SuperStoreData-230102-093001.xlsx)

### Tool
- Power BI Desktop (with Power Query for data transformation)

### Dashboard Breakdown

Page 1: Sales Overview
 - Aim: To give users an overview of total sales and transactions over time
    - Features:
      - Left- hand slicers allow users to change the report's context by selecting specific years, regions, or product categories
      - Top 10 and Bottom 10 States by Sales charts for quick comparison
      - Shipment Mode Analysis Table showing the percentage distribution for the top states

Page 2: Regional and Segment Insights
 - Aim: To help users understand performance trends across segments and states.
    - Features:
        - Sales Trend Chart by month to visualize how sales evolved overtime
        - Segment Performance Chart to compare sales across consumer, corporate, and house office segments
        - Top 10 states by sales chart: Users can click any state to view related details on segment distribution and shipment types
        - Average sales and transactions by day of the week for operational insights

Page 3: Advanced Sales Exploration (AI Visuals)
 - Aim: To use Power BI's AI capabilities for deeper pattern recognition
    - Features:
       - Key Influencers Visual: Automatically identifies factors influencing sales increases or decreases (e.g., product category or subcategory)
       - Decomposition Tree: Allow users to break down sales values by any dimension of their choice (year, category, or shipment mode)
       - Switch view option: Users can switch from this analysis page to a "Question and Answer" Page for custom exploration

Page 4: Q&A - Ask Your Data
 - Aim: To provide a natural language interface for users to ask questions about their data
    - Features:
       - "Ask a Question" Tab: Users can type custom questions (e.g., "Top 5 states by sales") and receive instant visual answers
       - Predefined Suggestion: Common Questions like "City below average sales" or "Loss-making states" to guide users.
       - "Back to Default" Button: Easy navigation back to the main analysis page

### Dashboard
[Superstore Dashboard- Ghiyathat Abdulrahman.pdf](https://github.com/user-attachments/files/22709811/Superstore.Dashboard-.Ghiyathat.Abdulrahman.pdf)

### Key Skills
- Power Query (data formatting and cleaning)
- Slicer interactivity
- Cross-filtering
- Trend Analysis
- Power BI AI Visuals
- Key Influencers and Decomposition Tree Analysis
- User Experience Design
- Utilized key influencers and Q&A visuals for insight automation

### Conclusion
The dashboard demonstrates data storytelling with Power BI- combining data transformation, visualization, and AI features to enable users to interact with and derive insights from sales data effortlessly.

## Reference
[ForesightBI Data Visualization essential with PowerBI](https://training.foresightbi.com.ng/courses/take/data-visualization-essentials-with-power-bi/texts/41406347-welcome)
