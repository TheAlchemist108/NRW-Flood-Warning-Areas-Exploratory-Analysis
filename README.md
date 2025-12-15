# NRW Flood Warning Areas Exploratory Analysis

**Comprehensive 11-step EDA pipeline for Natural Resources Wales (NRW) flood warning dataset**

## 📊 Overview
Automated exploratory data analysis script analyzing NRW flood warning areas dataset. Provides complete dataset profiling, geographic distributions, hierarchical structures, and bilingual (Welsh/English) naming completeness assessment.

## 🔬 Analysis Steps Delivered

### **Core Dataset Profiling (Steps 1-5)**
- **Step 1**: Dataset loading & validation
- **Step 2**: Structure overview (records, columns, schema)
- **Step 3**: Regional FWA distribution
- **Step 4**: Administrative area breakdown  
- **Step 5**: FWA naming uniqueness ratio

### **Spatial & Hierarchical Analysis (Steps 6-7)**
- **Step 6**: Top region × river/sea combinations (20 highest density)
- **Step 7**: Parent code hierarchy (top 20 parent-child relationships)

### **Bilingual & Quality Assessment (Steps 8-11)**
- **Step 8**: Welsh language name coverage (% complete)
- **Step 9**: Regional density metrics (FWAs, areas, river types)
- **Step 10**: Parent hierarchy complexity (geographic span)
- **Step 11**: Complete data quality dashboard

## 🎯 Key Insights Generated
```
✅ Regional FWA concentrations
✅ River/sea risk hotspots  
✅ Hierarchical parent structures
✅ Welsh name completeness (critical for NRW bilingual comms)
✅ Data quality metrics for modeling readiness
```

## 🛠️ Technical Details
- **Language**: Python 3.x
- **Dependencies**: `pandas` only
- **Input**: `NRW_FLOOD_WARNING.csv`
- **Output**: Console-formatted analysis report
- **Runtime**: <5 seconds on standard hardware

## 🌍 Environmental Impact
Built for **flood risk analysis** and **climate resilience research**. Supports NRW's flood warning infrastructure analysis for Wales' sustainability goals.

## 🚀 Usage
```bash
pip install pandas
python nrw_flood_analysis.py
```

## 📈 Perfect For
- **PhD research** in environmental data science
- **Flood risk modeling** preparation
- **NRW/EA reporting** and stakeholder presentations
- **AI-driven disaster prediction** pipelines

**Ready-to-deploy for production flood analytics workflows** 🌊🇬🇧

***

*Developed for advanced environmental data analysis | Compatible with Power BI, GIS integration*

Data Source - https://datamap.gov.wales/layers/inspire-nrw:NRW_FLOOD_WARNING#download-metadata-section
