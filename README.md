# Advertising Creative Analysis Agent  

## Overview  
The **Advertising Creative Analysis Agent** is a Python-based tool designed to analyze advertising creatives (images/videos) and correlate their visual features with performance metrics like Click-Through Rate (CTR). It extracts features using a pre-trained **ResNet50** model, applies **RandomForestRegressor** for correlation, and provides visual insights to help optimize ad performance.  

### **Key Features**  
- Extracts visual features (patterns, colors) from images and videos.  
- Identifies features strongly linked to higher CTR.  
- Provides graphical summaries for better understanding.  

## Architecture  
The tool follows a **modular pipeline**:  
1. **Data Ingestion** – Uploads creative files and performance data.  
2. **Content Analysis** – Extracts visual features using **ResNet50** and computes average colors.  
3. **Performance Correlation** – Uses **RandomForestRegressor** to find key factors affecting CTR.  
4. **Visualization** – Generates histograms and feature importance charts.  

## Setup & Installation  
### **Prerequisites**  
- **Google Colab** (Recommended)  
- **Python 3.7+**  
- Required libraries: OpenCV, Pandas, Matplotlib, TensorFlow, Sci-kit Learn.  

### **Steps to Run**  
1. **Open Google Colab** and access the provided script link.  
2. **Upload Input Files**:  
   - **Images/Videos** (e.g., `.jpg`, `.png`, `.mp4`).  
   - **Performance CSV** (should include `creative_id`, `click_through_rate`).  
3. **Run the Script** – Follow the prompts to process and analyze the creatives.  
4. **View Output** – Check debug logs, visualizations, and analysis results.  

## Interpretation of Visualizations  
- **CTR Distribution Histogram**: Highlights trends in ad performance.  
- **Feature Importance Chart**: Identifies key visual features influencing CTR.  

Use these insights to improve ad designs by focusing on impactful elements.  

---

📌 *This tool is ideal for marketers looking to optimize ad creatives based on data-driven insights!*  

