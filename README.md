Tableau Sales Dashboard Project:

Project Overview:
This project creates an interactive sales dashboard using Tableau to visualize Superstore sales performance by product category, region, and time period.

Files Included:
project-folder/
├── Superstore_Sales.csv                
├── dashboard_screenshot.pdf                    
└── README.md                    


Tools Required:
- Tableau Desktop(Public or Pro version)

Setup Instructions:

Method 1: Direct Tableau Import
1. Download the `Superstore_Sales.csv` dataset
2. Open Tableau Desktop
3. Connect to data: 
   - Click "Connect to Data" → "Text file"
   - Select the CSV file

Method 2: Python Data Prep (Optional)
```bash
pip install pandas
python prepare_data.py
```
 Dashboard Components:
1. Sales Trend: Line chart showing monthly sales performance
2. Regional Breakdown: Bar chart comparing sales across regions
3. Category Mix: Pie chart showing sales by product category
4. Interactive Filters: Region and Category selectors

