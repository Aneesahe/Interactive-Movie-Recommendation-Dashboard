# Interactive-Movie-Recommendation-Dashboard
A full-stack data science project that builds an end-to-end movie recommendation system wi
th an interactive Streamlit dashboard. Recruiters will love seeing real data ingestion, mo
deling, and deployment in one thin repository.
■ Project Highlights:
- Data Ingestion: Scrape and combine datasets from IMDb, TMDb API, and user ratings CSV.
- Data Processing: Clean, feature-engineer (genre embeddings, popularity, user profiles),
and store in SQLite.
- Modeling: Train a collaborative filtering model (e.g., Surprise library) and a content-b
ased model (TF-IDF on plot summaries).
- Dashboard: Streamlit web app with search, Top-N recommendations, interactive filters, an
d performance visualizations.
- Deployment: Dockerized app ready for `docker-compose up`.
■■ File Structure:
- README.md
- requirements.txt
- Dockerfile
- docker-compose.yml
- app.py
- src/
- notebooks/
- data/
- docs/
