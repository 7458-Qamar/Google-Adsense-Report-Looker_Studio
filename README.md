# Google-Adsense-Report-Looker_Studio
Google AdSense Analytics Dashboard

This repository contains a comprehensive Google AdSense analytics project built using a simulated multi-website dataset and visualized in Looker Studio. The project focuses on analyzing monetization performance, user behavior, traffic distribution, and ad quality metrics that are critical for publishers and analysts.

The dashboard is designed to reflect how AdSense performance is evaluated in real-world environments, going beyond basic revenue reporting to include engagement, viewability, and policy-risk indicators.

Project Purpose

Most AdSense dashboards stop at impressions, clicks, and CTR. This project was built to answer deeper questions such as:

Which websites and pages actually drive revenue?

How does traffic quality affect monetization?

Are ads viewable and healthy?

Are there early warning signals related to invalid clicks or coverage loss?

The goal is to demonstrate end-to-end analytics thinking, not just visualization.

Dataset Summary

Total rows: 500

Granularity: Daily

Data format: CSV

Websites: Multiple simulated publisher domains

Time range: Multi-month

The dataset is structured to closely resemble Google AdSense export data and includes both performance and quality metrics.

Key Metrics Included

Revenue USD

Impressions

Clicks

CTR

Sessions

Users (New and Returning)

Page Views

Bounce Rate

Average Session Duration

Viewability

Active View Measurable

Active View Viewable

Coverage Percentage

Invalid Clicks

Invalid Impressions

These metrics allow both monetization analysis and ad-quality monitoring.

Dashboard Structure

The dashboard is divided into four structured analytical sections.

Executive Overview

This section provides a high-level snapshot of overall AdSense performance.

Key elements include:

Total revenue, impressions, clicks, and CTR

Average viewability across all websites

Total invalid clicks

Revenue trend over time

Revenue contribution by website

Relationship between CTR and viewability

Distribution of impressions relative to clicks

This view answers the question:
Is AdSense monetization healthy overall?

Website Performance Analysis

This section focuses on comparing performance across websites and pages.

Key analyses include:

Revenue, impressions, clicks, CTR, and bounce rate by website

Revenue contribution by page URL

Sessions versus impressions comparison

Relationship between bounce rate and revenue

Relationship between invalid clicks and total clicks

This helps identify:

Top-performing websites

Pages that drive the most monetization

Whether traffic quality supports revenue growth

Traffic and Audience Insights

This section analyzes who the users are and how they generate revenue.

Key insights include:

Revenue by country using a geographic map

Revenue distribution by device type (mobile, desktop, tablet)

CTR comparison across browsers

New users versus returning users by browser

This section highlights:

High-value geographic regions

Device patterns affecting monetization

Browser-level engagement differences

Audience retention behavior

Ad Quality and Optimization

This section focuses on ad health, delivery efficiency, and policy risk indicators.

Key components include:

Clicks versus invalid clicks trend over time

Coverage percentage with a target benchmark

Active View measurable versus viewable impressions by website

Browser-level user behavior combined with ad metrics

This view is critical for:

Detecting abnormal click activity

Monitoring ad delivery health

Preventing long-term AdSense policy issues

Identifying optimization opportunities

Tools and Technologies Used

Looker Studio

Google AdSense-style CSV dataset

Calculated fields

Interactive filters and drill-downs

Time-series, bar charts, scatter plots, maps, and scorecards

Key Insights and Learnings

High CTR alone does not guarantee higher revenue

Viewability and engagement significantly impact monetization

Traffic volume without quality leads to diminishing returns

Invalid clicks must be monitored proactively

Dashboard structure and narrative improve decision-making
