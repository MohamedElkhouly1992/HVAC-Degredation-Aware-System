# Version 3 Final

This final patch adds true zone-specific occupancy aggregation with separate:
- occupancy density
- term schedule factor
- break schedule factor
- summer schedule factor

Supported zone types by default:
- Lecture
- Office
- Lab
- Corridor
- Service
- Custom

## Local one-pass
1. Unzip this package
2. Install:
   pip install -r requirements_v3.txt
3. Run:
   streamlit run streamlit_app.py
   or double-click run_app_v3.bat on Windows

## Mobile one-pass
Use the cloud-ready package and deploy unchanged to Streamlit Community Cloud.
