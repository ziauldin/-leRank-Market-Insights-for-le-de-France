# 🌍 ÎleRank: Interactive Market Ranking Map  

## 📝 Project Overview  
ÎleRank is a **geospatial data visualization** project designed to analyze and rank cities in **Île-de-France** based on **market performance metrics**, such as **revenue potential, occupancy rates, and seasonality trends**.  

This project involves:  
✔ **Web Scraping**: Extracting market data using a **custom Python web scraper**.  
✔ **Data Processing & Cleaning**: Structuring, validating, and filtering data for analysis.  
✔ **Ranking & Scoring**: Assigning a ranking score to cities based on market potential.  
✔ **Interactive Map Visualization**: Displaying ranked locations using **Folium & Leaflet.js**.  

---

## 🔍 **Data Collection & Processing**  
1️⃣ **Web Scraping & Data Extraction**  
- Developed a **custom Python scraper** to collect **market insights** from publicly available sources.  
- Extracted key data points, including:  
  - **Revenue Estimates**  
  - **Occupancy Trends**  
  - **Market Score Rankings**  

2️⃣ **Data Cleaning & Transformation**  
- Processed and structured data using **Pandas**, ensuring:  
  - Removal of **duplicates and null values**.  
  - Conversion of data types for numerical analysis.  
  - Merging multiple datasets for comprehensive insights.  

3️⃣ **Ranking Algorithm**  
- Cities ranked based on:  
  - **Revenue Potential**  
  - **Occupancy Rates**  
  - **Seasonality Trends**  
  - **Tourism & Demand Index**  
- Generated **Top 10, Top 20, Top 50, and Top 100** ranked locations.  

---

## 🗺️ **Interactive Map Features**  
✔ **Color-Coded Markers**:  
   - 🟢 **Green** → High-ranking cities.  
   - 🟠 **Orange** → Medium-ranking cities.  
   - 🔴 **Red** → Low-ranking cities.  

✔ **Hover Tooltips**: Display **Revenue, ADR, Occupancy Rate, and Market Score**.  
✔ **Dynamic Filtering**: View **Top 10, Top 20, Top 50, and Top 100** cities.  

---

## 🏗️ **Project Structure**  

📂 *static/* # Contains CSS, JS, and supporting files 

📂 *templates/* # HTML templates for web interface 

📄 *WebApp.html* # Interactive map (Leaflet.js + Folium) 

📄 *Web Scraper.ipynb* # Python notebook for web scraping 

📄 *ranked_city_scores.csv* # Processed dataset with ranked cities 

📄 *market_data_listing.csv* # Raw extracted data for analysis 

📄 *Web App User Manual.docx* # User guide for setup and usage


---

## 🚀 **Installation & Usage**  

### 1️⃣ **Prerequisites**  
Ensure you have **Python 3.8+** installed.  

### 2️⃣ **Install Dependencies**  
Run the following command to install required libraries:  

```
pip install requests beautifulsoup4 pandas folium flask
3️⃣ Run Web Scraper
Extract data using the custom scraper:

python Web_Scraper.ipynb
4️⃣ Launch Interactive Map
Start a local server to view the interactive map:


python -m http.server
Open in browser:

http://127.0.0.1:8000/WebApp.html

```
## 📈 Use Cases
### ✅ Real Estate Investors

Identify the best cities in Île-de-France for short-term rentals.
Make data-driven property investment decisions.
### ✅ Market Analysts & Researchers

Analyze market score rankings across different locations.
Study occupancy trends & revenue fluctuations.
### ✅ Data Science & GIS Professionals

Utilize geospatial analysis to extract actionable insights.
Extend functionality using machine learning for predictive modeling.
## 🤝 Collaboration
This project was developed in collaboration with Syed Ali Azzam, focusing on data scraping, analytics, and geospatial visualization.

### 👥 How to Contribute

Fork this repository.
Create a feature branch (git checkout -b feature-branch).
Commit your changes (git commit -m "Added new feature").
Push to GitHub (git push origin feature-branch).
Submit a Pull Request for review.
## 📜 License
This project is released under the MIT License. You are free to use, modify, and distribute this code for educational and analytical purposes.
