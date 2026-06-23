Project Overview:
This project performs **Exploratory Data Analysis (EDA)** on hotel booking data to uncover customer behavior, booking patterns, cancellation trends, and pricing strategies. The insights generated help hotel management improve occupancy, optimize pricing, and maximize revenue.

Business Problem:

Hotels face several challenges such as:
- High booking cancellation rates
- Revenue loss due to pricing inefficiencies
- Seasonal fluctuations in demand
- Different customer preferences across market segments
This project aims to provide data-driven insights to support better business decisions.

Tech Stack

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

Dataset Features
The dataset contains information related to:
- Hotel Type
- Lead Time
- Arrival Date
- Market Segment
- Number of Adults, Children, Babies
- Average Daily Rate (ADR)
- Booking Status
- Reservation Details
- Customer Information

Data Preprocessing

✔️ Missing Value Handling

✔️ Duplicate Removal

✔️ Data Type Conversion

✔️ Outlier Detection

✔️ Feature Understanding

Exploratory Data Analysis
The project includes:
🔹 Univariate Analysis
- Distribution of ADR
- Hotel Type Distribution
- Booking Status

🔹 Bivariate Analysis
- Market Segment vs ADR
- Hotel Type vs Booking Count
- Cancellation Rate Analysis

🔹 Multivariate Analysis
- Correlation Heatmap
- Feature Relationships

Key Performance Indicators (KPIs)

- Total Bookings
- Cancellation Rate
- Average Daily Rate (ADR)
- Average Lead Time
- Total Guests
- Booking Distribution
- Revenue Indicators

Visualizations Used

- Count Plot
- Histogram
- Scatter Plot
- Pie Chart
- Heatmap
- Box Plot
- Line Plot

Key Insights

✅ City Hotels receive more bookings than Resort Hotels.

✅ Longer lead times are associated with higher cancellation rates.

✅ Market segments significantly affect ADR.

✅ Seasonal trends impact occupancy and revenue.

✅ Customer behavior differs across booking channels.

Business Recommendations

- Implement deposit policies to reduce cancellations.
- Adopt dynamic pricing strategies.
- Focus on high-value customer segments.
- Optimize occupancy during low-demand periods.
- Monitor ADR to maximize revenue.

Project Structure
Hotel-Booking-Analysis/
│
├── HotelBook.ipynb
├── README.md
├── Dataset.csv
└── Images/

Results
This analysis provides valuable insights into customer booking behavior and pricing trends, enabling hotels to improve occupancy rates, optimize revenue management, and enhance customer satisfaction.

Libraries Used
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
