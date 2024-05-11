## Documenting the IPL Live Score Dashboard project:

### Overview:
The IPL Live Score Dashboard is a data visualization tool that provides real-time updates on IPL matches, including live scores, team details, player statistics, points table, and upcoming matches. The project involves API integration, data transformation, DAX measures, and dashboard creation using Power BI.

### Project Components:

1. **API Calling:**
   - Utilized Rapid API to access the Cricbuzz API for IPL match information.
   - Implemented GET requests to fetch match data using series ID.
   - Translated JavaScript code to M language for Power Query Editor.

2. **Data Transformation:**
   - Converted raw data into tabular format and expanded relevant columns.
   - Performed data cleaning, removed null values, and adjusted data types.
   - Created three tables: Live Team Score, Live Batting Score, and Live Bowling Score.
   - Merged custom tables containing logos and captains' information with live score tables.

3. **DAX Measures:**
   - Implemented DAX measures to calculate key performance indicators (KPIs) for the dashboard.
   - Aggregated data for runs, fours, sixes, matches won, lost, and points.

### Dashboard Screens:

1. **Live Scorecard:**
   - Displays batting and bowling scorecards with team filters.
   - Provides tooltips for detailed player information.
   - Includes team logos, captains' images, team scores, and KPIs such as runs, fours, and sixes.

2. **Points Table:**
   - Presents the current standings of IPL teams.
   - Features upcoming matches, team-wise KPIs, and captains' images.
   - Provides insights on team positions, matches needed to qualify, and current standings.

### Project Scope:

1. **Enhanced KPIs for Points Table:**
   - Add more insightful metrics on team positions and qualifications.
   - Provide live updates on matches needed to qualify and current standings.

2. **Player Stats in Tooltip:**
   - Replace current scores with player statistics in tooltips for better insights.

3. **Top Performer Insights:**
   - Fetch top run-getters, wicket-takers, etc., through stats API and display on the dashboard.

4. **Match Summary Instead of Detailed Scorecards:**
   - Simplify the Live Scorecard by providing match summaries and top performers from each team.

5. **Bug Fixes:**
   - Address issues with incorrect KPIs and captain's images in default mode.
   - Resolve the bug in upcoming matches table to display both home and away matches correctly.

### Learning Highlights:

1. **API Integration:** Learned to integrate external APIs for real-time data retrieval.
2. **Data Transformation:** Gained experience in cleaning, transforming, and structuring data for visualization.
3. **DAX Measures:** Developed expertise in creating calculated measures for complex calculations and KPIs.
4. **Dashboard Design:** Acquired skills in designing visually appealing and informative dashboards using Power BI.
5. **Bug Fixing:** Improved troubleshooting skills by identifying and resolving bugs in the dashboard.

### Conclusion:
The IPL Live Score Dashboard project demonstrated proficiency in data integration, transformation, visualization, and dashboard creation. It provided valuable insights into IPL matches and teams' performances, with scope for further enhancements to enrich user experience and analytical capabilities.
