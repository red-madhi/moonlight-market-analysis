🌙 Moonlight Market Analysis
This project analyzes ride patterns and geographic trends in late-night transportation using real Uber trip data.
It focuses on understanding where and when people are getting picked up — especially in nightlife-heavy areas.

🔍 Project Goals
Map high-density pickup zones after sunset 🌆

Visualize hotspots using Folium + Leaflet.js

Compare neighborhoods based on demand

Make the analysis reproducible and beginner-friendly

🧪 Try It Out
💻 Interactive HTML Map
🗺️ Click here to explore the interactive pickup map

📷 Static Preview

📂 Project Structure
kotlin
Copy
Edit
📁 notebooks/
    ├─ analysis.ipynb           ← Main analysis and data cleaning
    └─ plots/
        ├─ uber_map_preview.png ← Static map image
        └─ uber_map_full.html   ← Interactive Folium map (for GitHub Pages)
📁 data/                        ← CSV or other source data (not included)
📁 docs/                        ← Files rendered by GitHub Pages
⚙️ How to Run Locally
Clone the repo

Create a virtual environment and install requirements

Run notebooks/analysis.ipynb to generate maps

bash
Copy
Edit
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
jupyter lab
🤔 Why GitHub Pages?
We’re using GitHub Pages to host the interactive map so viewers can explore without running code locally. It lives inside the docs/ folder and updates every time we rebuild uber_map_full.html.

✨ Contributions Welcome!
Have an idea for other insights? Want to apply this approach to a different city or dataset? Fork this repo and go wild 🌐
Or just open an issue.
