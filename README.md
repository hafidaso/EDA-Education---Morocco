# Morocco Education System Analysis Project

## 📊 Project Overview

This comprehensive project provides a complete analysis of Morocco's education system from 2000-2030, including historical trends, international comparisons, and strategic forecasting. The project combines data collection, statistical analysis, visualization, and policy recommendations to support evidence-based education policy decisions.

---

## 📁 Project Structure

### 🔍 **Data Collection & Processing**
- **`collect-data.py`** - Automated data collection script from World Bank API
- **`education_data_2000_2024.csv`** - International education data (8,726 records)
- **`morocco_education_comprehensive_merged.csv`** - Morocco-specific data (873 records)
- **`unique_indicators.csv`** - Complete list of education indicators (89 indicators)

### 📈 **Analysis Notebooks**
- **`morocco_education_analysis.ipynb`** - Main comprehensive analysis (5,927 lines)
- **`International_Comparison_Analysis.ipynb`** - International benchmarking (1,415 lines)

### 📋 **Reports & Documentation**
- **`Morocco_Education_Analysis_Report_2000-2030.md`** - Main strategic report (1,015 lines)
- **`Morocco_Education_International_Comparison_Report_2024.md`** - International comparison report (295 lines)

### 🗺️ **Geographic Data**
- **`morocco_education_regional_data.csv`** - Regional-level education metrics (13 regions)
- **`morocco_education_provincial_data.csv`** - Provincial-level data (42 provinces)
- **`morocco_education_municipal_data.csv`** - Municipal-level analysis (21 municipalities)
- **`geoBoundaries-MAR-ADM1_simplified.geojson`** - Geographic boundaries for visualization

### 📚 **Reference Documents**
- **`EFAImpactReport2023-4.pdf`** - Education for All Impact Report (5.9 MB)
- **`IJER.MS.ID.000590.pdf`** - International Journal of Education Research (1.0 MB)
- **`10dfcb74-en.pdf`** - World Bank Education Report (614 KB)

---

## 🎯 **Key Components Analysis**

### 1. **Data Collection System** (`collect-data.py`)
```python
# Automated collection from World Bank API
- 9 comparison countries (TUN, DZA, EGY, ZAF, KEN, GHA, FRA, GBR, CAN)
- 98 education indicators covering 2000-2024
- Automated data validation and error handling
- Output: education_data_2000_2024.csv
```

**Key Features:**
- World Bank API integration
- Multi-country data collection
- Comprehensive indicator coverage
- Error handling and data validation

### 2. **Main Analysis Notebook** (`morocco_education_analysis.ipynb`)
**Comprehensive 5,927-line analysis covering:**

- **Historical Trends (2000-2024)**
  - Enrollment evolution across all education levels
  - Completion rate improvements
  - Gender parity achievements
  - Economic correlation analysis

- **Forecasting Models (2025-2030)**
  - Time series forecasting
  - Scenario planning
  - Policy impact modeling
  - Resource allocation projections

- **Statistical Analysis**
  - Correlation analysis
  - Regression modeling
  - Trend decomposition
  - Performance benchmarking

### 3. **International Comparison** (`International_Comparison_Analysis.ipynb`)
**1,415-line comparative analysis featuring:**

- **10-Country Benchmarking**
  - Regional peers (Tunisia, Algeria, Egypt)
  - African leaders (South Africa, Kenya, Ghana)
  - Developed benchmarks (France, UK, Canada)

- **15 Key Performance Indicators**
  - Enrollment rates (primary, secondary, tertiary)
  - Completion rates (primary, lower secondary, upper secondary)
  - Gender parity indices
  - Education spending (% GDP)
  - Economic indicators (GDP per capita, GINI index)

- **Standardized Year Comparisons**
  - Fair comparison methodology
  - Regional grouping analysis
  - Performance ranking system

### 4. **Geographic Analysis**
**Multi-level geographic data:**

- **Regional Level** (13 regions)
  - Average years of schooling
  - Education GINI index
  - Enrollment rates
  - Performance categories

- **Provincial Level** (42 provinces)
  - School infrastructure
  - Student-teacher ratios
  - Dropout rates
  - Female literacy rates

- **Municipal Level** (21 municipalities)
  - Urban/rural classification
  - Gender parity index
  - Distance to schools
  - Education rankings

### 5. **Strategic Reports**

#### **Main Report** (`Morocco_Education_Analysis_Report_2000-2030.md`)
**1,015-line comprehensive strategic document:**

- **Executive Summary**
  - Key achievements and challenges
  - Strategic recommendations
  - Policy implications

- **Historical Analysis**
  - Enrollment growth patterns
  - Completion rate evolution
  - Gender equity progress
  - Economic correlations

- **Forecasting Results**
  - 2025-2030 projections
  - Scenario planning
  - Policy impact modeling
  - Resource requirements

- **Strategic Recommendations**
  - Priority action areas
  - Implementation timeline
  - Resource allocation
  - Monitoring framework

#### **International Comparison Report** (`Morocco_Education_International_Comparison_Report_2024.md`)
**295-line focused comparative analysis:**

- **Performance Tables**
  - Detailed country rankings
  - Regional comparisons
  - Statistical analysis

- **Key Findings**
  - Morocco's strengths and challenges
  - Benchmarking results
  - Policy implications

---

## 📊 **Data Overview**

### **International Dataset** (`education_data_2000_2024.csv`)
- **8,726 records** covering 2000-2024
- **9 countries** (Morocco + 8 comparison countries)
- **98 indicators** across education, economic, and social domains
- **World Bank data** with standardized methodology

### **Morocco Dataset** (`morocco_education_comprehensive_merged.csv`)
- **873 records** of Morocco-specific data
- **Comprehensive coverage** of education system
- **Validated data** from multiple sources
- **Time series** from 2000-2024

### **Geographic Datasets**
- **Regional**: 13 administrative regions
- **Provincial**: 42 provinces with detailed metrics
- **Municipal**: 21 municipalities with granular data
- **Geographic**: GeoJSON boundaries for mapping

---

## 🔧 **Technical Specifications**

### **Data Sources**
- World Bank Education Statistics API
- Morocco Ministry of Education
- UNESCO Education Statistics
- National Statistical Offices

### **Analysis Tools**
- **Python**: pandas, numpy, matplotlib, seaborn
- **Statistical**: scipy, statsmodels
- **Visualization**: plotly, matplotlib
- **Geographic**: geopandas, folium

### **Methodology**
- Time series analysis
- Statistical correlation
- Regression modeling
- Scenario planning
- International benchmarking

---

## 🎯 **Key Findings Summary**

### **Major Achievements**
1. **Primary Completion**: Morocco ranks 1st globally (104.7%)
2. **Gender Parity**: Achieved in primary and secondary education
3. **Education Investment**: 3rd highest spending (6.0% of GDP)
4. **Enrollment Growth**: 279% increase in tertiary education

### **Critical Challenges**
1. **Upper Secondary Completion**: Only 38.5%
2. **Lower Secondary Completion**: 8th out of 9 countries
3. **Income Inequality**: 2nd highest GINI index (40.5)
4. **Learning Outcomes**: Below international standards

### **Strategic Priorities**
1. Address secondary education bottlenecks
2. Reduce income inequality
3. Improve learning outcomes
4. Enhance teacher quality

---

## 🚀 **Usage Instructions**

### **Running the Analysis**
```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn plotly geopandas

# Run data collection
python collect-data.py

# Execute main analysis
jupyter notebook morocco_education_analysis.ipynb

# Run international comparison
jupyter notebook International_Comparison_Analysis.ipynb
```

### **Accessing Reports**
- **Main Report**: `Morocco_Education_Analysis_Report_2000-2030.md`
- **International Comparison**: `Morocco_Education_International_Comparison_Report_2024.md`

### **Data Exploration**
- **International Data**: `education_data_2000_2024.csv`
- **Morocco Data**: `morocco_education_comprehensive_merged.csv`
- **Geographic Data**: Regional, provincial, municipal CSV files

---

## 📈 **Project Impact**

This comprehensive analysis provides:
- **Evidence-based policy recommendations**
- **International benchmarking insights**
- **Strategic forecasting for 2025-2030**
- **Geographic equity analysis**
- **Resource allocation guidance**

The project supports Morocco's education system development through data-driven insights and strategic planning for achieving national education goals by 2030.

---

## 👥 **Project Information**

**Author**: Hafida Belayd  
**Contact**: hafidabelaidagnaoui@gmail.com  
**LinkedIn**: https://www.linkedin.com/in/hafida-belayd  
**Date**: September 2025  

---

## 📝 **License & Usage**

This project is for educational and research purposes. Data sources are properly attributed and methodologies are transparent. The analysis provides evidence-based insights for policy development and academic research in education systems analysis.


