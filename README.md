# Digital Twin for Thailand Data Center Site Selection (MVP)

An AI-driven Digital Twin designed to simulate environmental, financial, and logistical variables for hyperscale data center optimization in Thailand.

## Key Insights Delivered
- **Optimal Placement:** Finds the most cost-effective province for development based on multi-criteria optimization.
- **Power Capacity Scalability:** Predicts achievable Megawatt bounds depending on regional grid capacity and proximity to infrastructure.
- **TCO per 1 MW:** Calculates total annualized operational and capital expenditure per Megawatt of IT load.
- **Cooling Cost Engine:** Simulates thermodynamics (air cooling overheads vs deep-sea water cooling profiles) to pinpoint precise cooling efficiency costs.

## Technical Stack
- **Language:** Python 3.10+
- **Data Engineering & Math:** NumPy, Pandas, SciPy Optimize
- **Geospatial Intelligence:** Folium (GIS Mapping & Visualization)

## Quick Start
1. Install dependencies: `pip install -r requirements.txt`
2. Run the Jupyter Notebook: `jupyter notebook digital_twin_mvp.ipynb`
