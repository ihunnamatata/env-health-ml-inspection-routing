# env-health-ml-inspection-routing

ML model for optimizing public health inspection routes using simulated restaurant data.

Environmental Health ML - Camden County Inspection Routing

This project uses simulated data from Camden County, NJ to analyze restaurant inspections. It applies ML-based risk scoring and geographic clustering to identify high-priority zones for environmental health interventions.
⸻
⚠️ Disclaimer

This dataset is fully synthetic and does not contain any real public health inspection data. It is intended for modeling and educational demonstration only.
⸻
What It Does
– Labels establishments as High, Medium, or Low risk
– Visualizes risk hot spots on an interactive map
– Uses KMeans clustering to group inspection zones
– Provides a baseline for route optimization and surveillance planning
⸻
How to Use
pip install -r requirements.txt
jupyter notebook notebooks/inspection_routing_camden.ipynb
⸻
Features
– Folium map of high-risk inspection sites
– Interactive popups with establishment metadata
– Clustering map using longitude + latitude
⸻
Folder Structure
– data/ – Synthetic inspection data
– notebooks/ – Jupyter ML notebook
– output/ – Saved map HTML, plots
– assets/ – Screenshots (optional for GitHub)
⸻
Author

Ihunna Amugo
DDS Candidate | MHA | MS | REHS | PhD(c) Computational Engineering
GitHub: @ihunnamatata
