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

🗂️ Project Structure
graphql
Copy
Edit
📁 moonlight-market-analysis/
├─ 📁 notebooks/
│  ├─ analysis.ipynb          # Main notebook with EDA and visualizations
│  └─ plots/
│     ├─ uber_map_preview.png # Static preview of Folium map
│     └─ pickup_heatmap.png   # Hour vs. Day heatmap
├─ 📁 docs/
│  └─ uber_map_full.html      # Interactive map hosted via GitHub Pages
├─ 📁 data/                    # (Optional) Raw CSV data files
├─ README.md
└─ requirements.txt
⚙️ How to Run Locally
Clone the repository and set up the environment:

bash
Copy
Edit
git clone https://github.com/red-madhi/moonlight-market-analysis.git
cd moonlight-market-analysis
python -m venv .venv
source .venv/bin/activate   # Use `.venv\Scripts\activate` on Windows
pip install -r requirements.txt
jupyter lab
Open notebooks/analysis.ipynb to explore the analysis and generate visualizations.

🤔 Why GitHub Pages?
We use GitHub Pages to host the interactive Folium map so anyone can explore it without needing Jupyter or Python.
The map lives inside the docs/ folder and gets updated whenever the HTML file is regenerated.

✨ Contributions Welcome
Want to tweak the visuals? Try it on a different city? Add cool features?
Fork the repo and go wild, or open an issue with suggestions or bugs.
We like maps. You like maps. Let’s do cool map stuff.



