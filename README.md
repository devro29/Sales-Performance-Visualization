# Sales-Performance-Visualization
Sales Revenue Analysis Using Waterfall and Tree Map Charts


# Objective
To visualize company sales performance over a 12-month period using two complementary charts:

Waterfall Chart – Shows monthly changes in revenue and final cumulative outcome

Tree Map – Displays proportional sales share of each month, highlighting peak periods


# Tools Used
Matplotlib: for static plotting (Waterfall Chart)

Plotly Express: for interactive and structured visualization (Tree Map)

Pandas & NumPy: for data preparation and computation

Python

# Data:
January: $12,500  
February: $15,300  
March: $14,200  
April: $17,800  
May: $16,400  
June: $19,000  
July: $20,500  
August: $18,900  
September: $17,200  
October: $15,800  
November: $22,100  
December: $21,500


# Visualization 1 – Waterfall Chart: Monthly Sales Fluctuations

January's starting revenue: $12,500

Each month's value represents a net change from the previous month

Bars are colored to reflect:

- Green for revenue growth
- Red for revenue decline
- Blue (or neutral) for cumulative total (final bar)

Features:

Bar annotations for exact change values

Legend to indicate performance direction

Final bar for cumulative revenue

Useful for identifying volatile months and overall growth trends


# Visualization 2 – Tree Map Chart: Monthly Revenue Distribution
Monthly absolute revenue values from January to December

Size of each block is proportional to total monthly sales

Color gradient shows:

- Darker shade = Higher revenue
- Lighter shade = Lower revenue
- The month with highest revenue is distinctly highlighted

Features:

- Interactive hover labels (month + value)
- Hierarchical layout for clarity
- Helps in identifying seasonal performance peaks and lows

# Insights
The Waterfall Chart clearly highlights months with inconsistent sales performance, helping spot risks and revenue drop-offs.

The Tree Map provides an intuitive visual comparison of each month’s total contribution, making it ideal for presentations and summaries.

Together, these charts offer a comprehensive picture of sales behavior for strategic planning.


# Visualization 3 – Customer Overlap Across Marketing Campaigns

This interactive bar chart highlights how customers engaged across different marketing channels such as Email, Social Media, and Mobile. Each bar represents a unique segment based on single or multiple-channel engagement combinations. This visualization presents an analysis of how a Travitinerary's customers interact with three key marketing channels: Email, Social Media, and Mobile Campaigns, based on a dataset of 5,000 unique customers.

1. Exclusive Channel Engagement
A substantial number of customers are engaging through only one channel:

Email Only: Customers reachable solely via email represent a traditional but still relevant segment.

Social Only: This group is indicative of a younger or digitally-native audience preferring platforms like Instagram, Facebook, etc.

Mobile Only: These customers are engaging via SMS or app notifications—likely mobile-first users.

High exclusivity in any one channel may indicate missed cross-channel opportunities and potential for broader engagement strategies.

2. Two-Channel Overlaps

These customers are more engaged and are likely moving through a multi-touch journey. These groups are crucial for retargeting and funnel acceleration, as they’re already interacting on more than one front.

The overlaps between:

Email & Social
Email & Mobile
Social & Mobile


3. Highly Engaged Customers (All Three Channels)
The segment of users who engage with all three channels—Email, Social, and Mobile—is relatively smaller but extremely valuable. These are the most engaged, multi-channel customers, and likely to be brand loyal or high-value customers. This segment is ideal for premium offerings, early product access, referral incentives, and deeper personalization.

4. Strategic Opportunities
If the number of "Only Social" or "Only Mobile" users is high, Travitinerary may be under-leveraging traditional touchpoints like email campaigns. Conversely, if "Email Only" dominates, modern channels (mobile push, social media) may need better integration. Identifying the least represented segments indicates where marketing investment or optimization is lacking.





