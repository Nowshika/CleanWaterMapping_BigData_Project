# 💧 Mapping Access to Clean Water in Rural Areas
### Big Data Analytics Mini Project  
**Author:** Nowshika Mirza R  
**SDG Goal:** 6 – Clean Water and Sanitation  

---

## 🧭 Overview
This mini project analyzes and visualizes **access to clean water in rural areas** using **Big Data Analytics** techniques.  
By computing a **Water Quality Index (WQI)** and classifying regions as *High*, *Medium*, or *Low Access*, the project supports **SDG 6: Clean Water and Sanitation**, promoting sustainable resource management and responsible data use.

---

## 📊 Dataset
- **Source:** [Global Water Potability Dataset – Kaggle](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- **File Used:** `global_water_quality.csv`
- **Key Attributes:**
  - `ph`, `Hardness`, `Solids`, `Chloramines`, `Sulfate`, `Conductivity`, `Turbidity`
  - `Potability` (0 = Not Drinkable, 1 = Drinkable)
  - Derived Features: `Water Quality Index (WQI)`, `Water Access Level`

---

## 🛠️ Tools & Libraries
| Library | Purpose |
|----------|----------|
| **Python 3** | Programming and analysis |
| **Pandas, NumPy** | Data cleaning & computation |
| **Matplotlib, Seaborn** | Static visualizations |
| **Folium** | Interactive geographical map |
| **Jupyter Notebook** | Development environment |

---

## ⚙️ Steps & Methodology
1. **Load & Clean Data:** Handle missing values, normalize parameters.  
2. **Feature Engineering:** Compute *Water Quality Index (WQI)* and classify access levels.  
3. **Visualization:**  
   - WQI distribution histogram  
   - Bar chart for water access levels  
   - Correlation heatmap  
   - Rainfall vs. WQI scatter plot  
   - **Interactive Folium Map** to visualize access by region  
4. **Insight Generation:** Identify regions needing improvement and analyze parameter effects on WQI.

---

## 🗺️ Output Files
| File | Description |
|------|--------------|
| `Mapping_Clean_Water.ipynb` | Main project notebook |
| `global_water_quality.csv` | Dataset file |
| `rural_water_quality_map.html` | Interactive geographic map (open in browser) |
| `README.md` | Project documentation |

---

## 💡 Insights
- Regions with **high solids or low pH** show poor water quality.  
- **Rainfall** correlates with improved WQI in several areas.  
- Data-driven insights can guide **policy and infrastructure** decisions.  

---

## 🌍 SDG 6 Impact
Supports **Sustainable Development Goal 6** – *Ensure availability and sustainable management of water and sanitation for all.*  
Encourages **data-driven sustainability** and responsible use of natural resources.

---

## 🧩 How to Run
```bash
pip install pandas numpy matplotlib seaborn folium
jupyter notebook
