# AWS-QuickSight-Flight-Cancellation-Analytics
📊 Dashboard Overview
The dashboard provides comprehensive insights into flight cancellations including:

Airline-wise cancellation distribution
Geographical visualization of cancellation reasons
Origin-to-cancellation reason flow analysis
Monthly cancellation trends with ML-powered forecasting
Anomaly detection for weather-related cancellations
🛠️ Components
Data Visualizations
Bar Chart: Cancelled flights by carrier
Geospatial Map: Cancellation reasons by destination
Sankey Diagram: Origin airport to cancellation reason flow
Line Chart: Monthly trends with forecasting
Pie Charts: Carrier-wise cancellation reason distribution
Interactive Features
Origin airport filter
Flight date filter
Carrier name filter
Cross-visual filtering actions
ML Insights
Anomaly detection for cancellation patterns
Forecasting for future cancellation trends
📝 Prerequisites
AWS Account with QuickSight Enterprise Edition
SPICE capacity available
Required datasets:
all-cancelled-flights.csv
cancellation-codes.csv


Data Ingestion
- Upload all-cancelled-flights.csv to QuickSight
- Import into SPICE
- Add cancellation-codes.csv
- Configure join between datasets

Data Preparation
- Rename columns (DEST → DESTINATION)
- Convert data types (OP_CARRIER_FL_NUM to String)
- Create geospatial fields (ORIGIN_GEO, DESTINATION_GEO)
- Clean up joined fields

Dashboard Creation
- Create new analysis
- Add visualizations
- Configure filters
- Add ML insights
- Create multiple sheets


📈 Visualization Details
Sheet 1: Summary

Cancelled Flights by Carrier (Bar Chart)
Cancellation Reason by Destination Airport (Map)
Origin Airport Cancellation Reasons (Sankey)
Cancelled Flights per Month (Line Chart with Forecast)
Sheet 2: Cancellation by Airline

Carrier Cancellation Reasons (Pie Charts)
Detailed Data Table
ML-powered Anomaly Detection
🔄 Interactive Features
Filter Actions on visualizations
Drill-down capabilities in pie charts
Cross-sheet filtering
Dynamic date range selection
🎯 Key Metrics
Total cancellations by airline
Geographic distribution of cancellations
Temporal patterns in cancellations
Cancellation reason distribution
Anomaly detection in weather-related cancellations
📚 Documentation
Detailed documentation is available for:

Data preparation steps
Visualization creation
Filter configuration
ML insight setup
Dashboard publishing

📧 Contact
For questions or feedback, please open an issue in this repository.
