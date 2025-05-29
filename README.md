
# 🌍 Geospatial Analytics & Sentiment Mapping

This project combines geospatial data visualization with natural language processing to analyze both humanitarian trends and public sentiment across regions.

## 📘 Overview

- Visualizes refugee migration trends (1990–2023) using World Bank and UCDP conflict datasets.
- Performs sentiment analysis on tweets related to ChatGPT using TextBlob and VADER.
- Integrates geospatial joins and statistical analysis to provide region-wise insights through interactive maps and plots.

## 🔍 Features

- 🗺️ Choropleth maps showing global refugee distribution
- 📈 Conflict vs. migration trend analysis
- 💬 Geotagged Twitter sentiment mapping
- 📍 Polarity and subjectivity visualization
- 🧠 Regional clustering of positive, negative, and neutral sentiment

## 🛠️ Tech Stack

- Python
- Pandas, GeoPandas
- TextBlob, VADER (NLP)
- Matplotlib, Seaborn
- Folium, Shapely

## 📊 Datasets Used

- [World Bank Refugee Population Data](https://data.worldbank.org/indicator/SM.POP.REFG)
- [UCDP Conflict Data](https://ucdp.uu.se/)
- Public tweets via Twitter API (ChatGPT-related)

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/geospatial-sentiment-mapping.git
   cd geospatial-sentiment-mapping
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook
   ```

> Ensure Twitter API credentials are set if running tweet sentiment modules.

## 📌 Project Goals

- Integrate spatial and emotional analysis into a single pipeline
- Explore the relationship between geography and public sentiment
- Generate policy-relevant insights from open data and social platforms

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
