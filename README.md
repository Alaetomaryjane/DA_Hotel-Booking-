# Hotel Booking Analysis

This project explores patterns in hotel booking data to understand reservation trends, cancellation behaviour, and other influencing factors. The insights are based on a dataset of hotel bookings, focusing on cancellations, averages daily rates (ADR), and customer segments.

## Project Objectives
  1. Understand booking patterns: Analyze trends in reservations and cancellations across different hotels, months, and market segments.
  2. Explore customer behaviour: Identify factors influencing cancellations and ADR variations.
  3. Visualize trends: Use data visualization to present key findings clearly and effectively.

---

## Data Exploration and Cleaning
- **Dataset Details**:
  The dataset contains information about bookings for two hotel types: Resort and City hotels.
- **Data Cleaning**:
  - Removed unnecessary columns (`agent`, `company`) and null values.
  - Filtered out extreme outliers in ADR (>5000).
  - Converted `reservation_status_date` to datetime format.

  ---

## Key Insights 
### Reservation and Cancellation Trends
- **Overall Cancellations**:
  - ~40% of all bookings were canceled.
  - City hotels have a higher cancellation rate (42%) compared to resort hotels (28%).
- **Monthly Trends**:
  - Peak reservations occur in `July` and `August`, coinciding with high cancellationns.
  - Off-peak seasons (December-Feburary) show fewer reservations and cancellations.

---

### Average Daily Rate (ADR) Analysis
- **Hotel Type Comparison**:
  - Resort hotels have higher ADRs during peak periods, showing more seasonal fluctuations.
  - City hotels exhibits relatively stable ADRs year-round.
- **Cancellation vs Non-Cancellation**:
  - Canceled bookings generally have higher ADRs, while non-canceled bookings have more consistent rates.

### Market Segment Analysis
- Most reservations originate from **Online Travel Agencies** (OTA), contributing significantly to cancellations.

---

## Visualizations
- **Reservation Status**: Bar and line charts show the reservation trends by month, cancellation status and hotel type.

![image](https://github.com/user-attachments/assets/6d03109e-a24d-463d-be21-a2da4ea4b7b4)

  
- **ADR Trends**: Plotted ADR over time for both hotel types and for canceled/non-canceled bookings.

![image](https://github.com/user-attachments/assets/a3c062b9-bfb3-4761-8358-3e372026a23f)

  
- **Market Segments**: Pie charts highlights contributions from different customer sources and their cancellation behaviour.

---

## Conclusion
This analysis provides actionable insights into booking behaviours and cancellation trends. It highlights critical factors such as pricing, seasonality, and customer segments, which can help improve operational efficiency and revenue management strategies for hotels








