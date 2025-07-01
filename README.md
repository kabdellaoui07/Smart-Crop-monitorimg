# Smart-Crop-monitoring

This project combines remote sensing analysis in Google Colab with smart automation in n8n to monitor a selected agricultural field using Sentinel-2 images.

## 🛰️ Features:
- Automatic calculation of spectral indices: NDVI, NDWI, EVI, SAVI
- Python script in Google Colab processes new satellite images
- Data is sent to n8n via Webhook
- n8n checks for thresholds (e.g., crop maturity, vegetation drop)
- Telegram Bot sends alerts when changes are detected
- All results are saved in Google Sheets

## 🔗 Technologies:
- Python (Google Colab)
- Google Earth Engine (GEE)
- n8n (Automation)
- Telegram Bot API
- Google Sheets API
- Sentinel-2 imagery
- Remote Sensing

## 🧪 Use Case:
Real-time vegetation monitoring based on the latest satellite image, for agriculture or forest health, using a selected field of interest.

## 📁 Files:
- ndvi_monitoring.ipynb: The full analysis script
- n8n-workflow.png: Workflow logic
- README.md: This description

