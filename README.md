# Hotel Performance Analytics

A Power BI dashboard for analyzing hotel bookings, revenue, occupancy, and operational performance. The report combines Power Query transformations with DAX measures to turn booking data into actionable insights.

EXPLORE DASHBOARD AT: https://app.powerbi.com/view?r=eyJrIjoiZWM3MDQxMzktYzI3NC00NzU3LWJhYTctMzlhNGI5NDNkNDZhIiwidCI6ImVlMjkyOTc3LTdiNTgtNGRmNC04MTM4LTUwZDBkZTdkMjhkOCIsImMiOjh9

## Dashboard highlights

- **Core KPIs:** Revenue, RevPAR, ADR, occupancy, and realization, with comparisons to the previous period.
- **Performance breakdowns:** Weekly trends, room-class performance, booking channels, room utilization, and revenue.
- **Interactive analysis:** Filter by date, week, room class, and booking platform.
- **Hotel detail:** Compare capacity, successful bookings, cancellations, no-shows, and key rate metrics.

## Descriptive findings

- “Others” and MakeYourTrip account for 60.90% of bookings; breaking down “Others” would clarify channel concentration.
- Reported cancellation rates are consistently high across channels (about 24.8%), supporting further analysis by lead time, rate plan, room class, and rebooking.
- Presidential rooms lead in reported ADR and RevPAR, while occupancy is broadly similar across room classes.
- Weekly occupancy and RevPAR fluctuate despite relatively stable ADR. Week 32 has high occupancy and RevPAR but unusually low reported revenue, so validate its completeness, revenue scope, and denominator before drawing conclusions.

## Data model

The model includes booking and aggregated-booking facts, with supporting hotel, room, and date dimensions. A dedicated measures table organizes the DAX calculations.

## Built with

- Microsoft Power BI
- Power Query (data preparation)
- DAX (measures and period comparisons)
