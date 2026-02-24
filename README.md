Payroll vs Performance in MLB (2011–2024)
Overview

This mini project explores the relationship between team payroll and on-field performance in MLB (Major League Baseball) from 2011 to 2024.

The main goal is to understand whether spending more on payroll is associated with better sporting results, and to analyze how payroll structure may also affect team outcomes.

Project Objective

The core question behind this project is:

Does higher payroll lead to better performance?

To answer this, I analyzed team-level payroll and performance data using Excel and Power Query, focusing on:

payroll trends over time

payroll vs win percentage

team efficiency (cost per win)

payroll allocation structure (active, injured, retained, buried)

Tools Used

Excel

Power Query

Pivot Tables

Excel Charts / Visualizations

Dataset

Scope: MLB team-level data

Period: 2011–2024

Granularity: One row per team per season

Main fields used

Team / Team Name

Year

Average Age

Total Payroll Allocations

Active 26-Man

Injured

Retained

Buried

Wins

Losses

Postseason

Data Preparation (Power Query + Excel)

Data cleaning and preparation were done in Power Query, followed by metric creation in Excel.

Cleaning steps

Standardized data types (numbers, text, etc.)

Handled missing values in payroll allocation subcategories (Injured, Retained, Buried) as 0 when applicable

Checked consistency between total payroll and payroll subcomponents

Prepared the dataset for pivot-table analysis and charting

Derived columns created in Excel

Games = Wins + Losses

Win % = Wins / Games
(used to compare seasons consistently, especially 2020)

Cost per Win = Total Payroll Allocations / Wins

Payroll Parts Sum = Active + Injured + Retained + Buried

Payroll Diff = Total Payroll - Payroll Parts Sum (validation check)

% Active / % Injured / % Retained / % Buried = payroll structure ratios

Key Analyses
1) League Average Payroll Over Time

Analyzed how average team payroll changed across MLB from 2011 to 2024.

2) Payroll vs Performance (Win %)

Used a scatter plot to assess whether higher payroll is associated with higher Win % (win percentage).

3) Team Efficiency (Cost per Win)

Compared teams based on how much they spent per win to identify:

efficient teams (lower cost per win)

inefficient teams (higher cost per win)

4) Payroll Structure by Season Outcome

Compared payroll allocation structure across season outcomes:

Playoff teams / non-playoff teams
or

Division winners / Wildcard teams / non-playoff teams

This helps evaluate whether how payroll is allocated matters as much as total payroll.

Key Findings

Payroll appears to have a positive but not perfect relationship with performance.

Teams with similar payroll levels can have very different results, which suggests that payroll alone does not explain performance.

Team efficiency varies significantly: some teams achieve strong performance with lower payrolls, while others underperform despite higher spending.

Payroll allocation structure may also play an important role in team outcomes.

Limitations

Payroll does not fully explain team performance (injuries, player development, roster quality, trades, coaching, and other factors also matter).

This project shows association, not causation.

The 2020 season was shortened, so Win % was used instead of raw wins for cross-season comparison.
