# 🌙 Moonlight Market Analysis

This project analyzes ride patterns and geographic trends in late-night transportation using real Uber trip data.  
It focuses on understanding **where and when** people are getting picked up — especially in nightlife-heavy areas.

---

## 🔍 Project Goals

- Map high-density pickup zones after sunset 🌆  
- Visualize hotspots using Folium + Leaflet.js  
- Compare neighborhoods based on demand  
- Make the analysis **reproducible** and beginner-friendly  

---

## 🧪 Try It Out

### 💻 [Explore the Interactive Map](https://red-madhi.github.io/moonlight-market-analysis/uber_map_full.html)  
*No setup required — view in browser!*

### 📷 Static Preview  
![Pickup Map Preview](notebooks/plots/uber_map_preview.png)

## 📁 Project Structure

📁 notebooks/
├── analysis.ipynb       - Main notebook with EDA and mapping  
└── plots/
    ├── pickups_by_hour.png  
    ├── pickup_heatmap.png  
    └── uber_map_preview.png

📁 data/                 - (Optional) Place source CSV files here  
📁 docs/  
└── uber_map_full.html   - Interactive Folium map for GitHub Pages

## ⚙️ How to Run Locally

1. Clone the repo:
   git clone https://github.com/red-madhi/moonlight-market-analysis.git  
   cd moonlight-market-analysis

2. Create a virtual environment:
   python -m venv .venv  
   source .venv/bin/activate     # On Windows: .venv\Scripts\activate

3. Install requirements and launch Jupyter:
   pip install -r requirements.txt  
   jupyter lab

4. Open notebooks/analysis.ipynb and run all cells to generate plots and maps

## 🤔 Why GitHub Pages?

We use GitHub Pages to host the interactive map so others can explore without running code locally.  
It updates whenever notebooks/analysis.ipynb saves uber_map_full.html into the docs/ folder:

https://red-madhi.github.io/moonlight-market-analysis/uber_map_full.html
