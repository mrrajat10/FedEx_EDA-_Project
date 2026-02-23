# FedEx_EDA_Project
Project Summary

This project presents a comprehensive Exploratory Data Analysis (EDA) of FedEx’s global logistics dataset to evaluate delivery performance, freight cost behavior, shipment modes, fulfillment methods, and contractual trade structures (INCO terms). The objective was to transform raw operational data into actionable business insights for logistics optimization.

The analysis identified that Air transport is the most reliable shipment mode with the lowest delay rate, while Truck and Ocean modes exhibit higher variability and delay risk. Direct Drop fulfillment demonstrates stronger on-time consistency compared to Regional Distribution Centers (RDCs), which introduce greater delivery fluctuation. Freight cost shows a strong positive correlation with shipment weight, although higher freight spend does not necessarily guarantee improved delivery performance. Additionally, operational ownership is highly centralized, and EXW is among the most consistently used INCO terms.

Outlier detection and data cleaning were performed to ensure reliable statistical interpretation. Multivariate analysis was applied to examine how shipment mode influences the relationship between weight and freight cost. Categorical comparisons were used to evaluate delivery status across fulfillment strategies.

Technologies & Libraries Used

Pandas – Data cleaning, preprocessing, grouping, aggregation, and filtering

NumPy – Numerical computations and conditional operations

Matplotlib – Custom visualizations, styling, annotations, and layout control

Seaborn – Statistical visualizations (boxplots, violin plots, countplots, multivariate scatterplots)

Plotly Express – Interactive visualizations and enhanced exploratory charts

Plotly.io – Rendering and export configuration

Kaleido – Static image export of Plotly figures

Jupyter Notebook – Interactive analysis and visualization environment

Key Business Recommendations

Prioritize Air transport for time-sensitive and critical shipments.

Optimize RDC operational processes to reduce delivery variability.

Monitor high-weight and high-cost shipments separately for risk management.

Maintain a balanced logistics strategy: Air for urgency, Ocean for bulk, Truck for regional distribution, and Air Charter for emergencies.
